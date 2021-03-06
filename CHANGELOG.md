# 1.4.1 / _Not released yet_


# 1.4.0 / 2013-05-14

- First community site release! Replaces the earlier "debian" cookbook.
    * Huge thanks and respect to [Guilhem Lettron](https://github.com/guilhem)
      for giving the community site cookbook name for us.
    * This version can be used as a drop-in replacement with default
      attributes in some cases, but any custom node attributes for the old
      cookbook **do not work**.
    * Please read the [readme](README.md) for usage instructions.
- Improve the readme
- Specify platform versions for Fauxhai in ChefSpec tests

# 1.3.2 / 2013-05-07

- Fix non-lsb codename detection on first Wheezy release ([GH-6])

# 1.3.0 / 2013-05-06

- Use [http.debian.net](http://http.debian.net/) as a default mirror
- Don't rely on `lsb_release` being installed ([GH-6])
- More ChefSpec tests
- Add simple Test Kitchen 1.0 setup

# 1.2.0 / 2013-03-22

- Use new backports URL from Wheezy on ([GH-5])
- Include apt recipe only after sources.list has been updated
- Add chefspec tests ([GH-2])
- Other test and Vagrant environment improvements

# 1.1.2 / 2013-02-06

- Use `apt_preference` resource to create the repo pinning rule
- Remove the `apt-get update` workaround ([GH-3])
- Add foodcritic and Knife cookbook tests ([GH-2])
- Test with latest Chef 10 and 11 releases on Travis

# 1.1.0 / 2013-01-21

- Workaround for apt cookbook not running `apt-get update` on apt_repository
  updates ([GH-3])
- Vagrant setup for manual testing ([GH-1])

# 1.0.0 / 2013-01-18

- Initial public release


[GH-1]:  https://github.com/reaktor/chef-debian/issues/1  "Issue 1"
[GH-2]:  https://github.com/reaktor/chef-debian/issues/2  "Issue 2"
[GH-3]:  https://github.com/reaktor/chef-debian/issues/3  "Issue 3"
[GH-5]:  https://github.com/reaktor/chef-debian/issues/5  "Issue 5"
[GH-6]:  https://github.com/reaktor/chef-debian/issues/6  "Issue 6"
