# Managing Packages

## Package Updates
### Excluding packages from updates
Add the line exclude= in one of /etc/yum.conf or /etc/um.repos.d/<reponame>.repo
  ```
  exclude=centos-release*
  ```
  
  ### Forcing update of an excluded package
  ```
  yum uppdate --disableexcludes=[all|main|repoid]
  ```
  
  
