# vagrant-parallels-mono-aspnetvnext

A vagrant box for ASP.NET VNEXT & mono running on the vagrant-parallels provider

## Installation
First, make sure that you have [Parallels Desktop for Mac](http://www.parallels.com/products/desktop/)
and [Vagrant](http://www.vagrantup.com/downloads) properly installed.

To install vagrant-parallels:

```
$ vagrant plugin install vagrant-parallels
```

1. Run `vagrant up`
2. Run `vagrant ssh`
3. Run `kpm restore'
4. Navigate to `src\helloworldweb'
5. Type `k web`
6. Open a browser and type `http://localhost:1234`
