## 0.7.4 / 2013-03-28

### Improvements

* Drop `vagrant ssh -c` & communicate directly via SSH. ([@fnichol][])


## 0.7.3 / 2013-03-28

### Bug fixes

* Calling #destroy should not memoize #create_vagrantfile. ([@fnichol][], [@sandfish8][])


## 0.7.2 / 2013-03-23

### Bug fixes

* Wrap strings for data_bags_path and roles_path in Vagrantfiles. ([@fnichol][])


## 0.7.1 / 2013-03-23

### Bug fixes

* Depend on test-kitchen ~> 1.0.0.alpha.1 to get API updates. ([@fnichol][])


## 0.7.0 / 2013-03-22

### New features

* Pull request [#7][]: [Breaking] Support Vagrant 1.1+ and remove vagrant gem dependency. ([@fnichol][])
* Pull request [#8][]: Add dependency checks for Vagrant and berkshelf-vagrant plugin (if necessary). ([@fnichol][])


## 0.6.0 / 2013-03-02

The initial release.

<!--- The following link definition list is generated by PimpMyChangelog --->
[#7]: https://github.com/opscode/kitchen/issues/7
[#8]: https://github.com/opscode/kitchen/issues/8
[@fnichol]: https://github.com/fnichol
[@sandfish8]: https://github.com/sandfish8