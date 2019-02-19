# instalación de foreman en centos 7<h1>
  
  **Reositorios requeridos**
  *para la instalación de foreman(al momento de ingresar estos comando deben de ser sobre el usuario root)
 1. yum -y localinstall http://fedorapeople.org/groups/katello/releases/yum/3.10/katello/el7/x86_64/katello-repos-latest.rpm
 2. yum -y localinstall http://yum.theforeman.org/releases/1.20/el7/x86_64/foreman-release.rpm
 3. yum -y localinstall https://yum.puppetlabs.com/puppetlabs-release-pc1-el-7.noarch.rpm
 4. yum -y localinstall http://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
 5. yum -y install foreman-release-scl python2-django
