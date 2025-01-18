# 202x.pyconuk.org
PyCon UK 202x website

If you're starting with this base, you'll need to update the dates, etc in the _config.yml to reflect those for the current year.
You probably only need to care about the stuff that is called con_<something>.
You'll also need to put appropriate links everywhere you find "There will be a link".
Also, don't forget to update the 'Schedule' link in the header when the schedule is available.

## Building Locally
### Installing Jekyll

This site is made using [Jekyll](https://jekyllrb.com).
Jekyll is a static site generator written in ruby.
To build the project we first need to check that we have Jekyll's requirements installed.

These are:

* [Ruby](https://www.ruby-lang.org/en/downloads/) (tested with Ruby 2.7- you will also need the development headers)
* [RubyGems](https://rubygems.org/pages/download)
* [GCC](https://gcc.gnu.org/install/)
* [Make](https://www.gnu.org/software/make/)

On Ubuntu 20.04 this can be achieved by: sudo apt-get install -y ruby ruby-dev gcc make build-essential

You can check if you have these installed by typing `<command> -v` in your terminal.
If the program is available on your system then you should see the version of the program that is installed outputted in your terminal.

For example if Ruby in installed and you run `ruby -v`, you should get output like this `ruby 2.7.0p0 (2019-12-25 revision 647ee6f091) [x86_64-linux]`.
If RugbyGems is not installed an you run `gem -v` you should get an error like this `bash: gem: command not found`

See the [Jekyll documentation](https://jekyllrb.com/docs/installation/) for more information on install Jekyll and its requirements.

Now that you have all of Jekyll's requirements installed you can install and run Jekyll:

```bash
./run
```

This will start a webserver on [http://127.0.0.1:4000/](http://127.0.0.1:4000/).
To view the website open [http://127.0.0.1:4000/](http://127.0.0.1:4000/) in your favorite web browser.
This will also automatically rebuild the project when a change to the source is detected.


## Help! Bundler is mucking around and won't install anything (execution expired)

You may need to disable IPv6 as apparently bundler is rather shoddy.

On Ubuntu:
```bash
echo "Showing current IPv6 state"
for conf_entry in all default lo; do
  sysctl net.ipv6.conf.${conf_entry}.disable_ipv6=1
done
echo "Updating IPv6 state"
for conf_entry in all default lo; do
  sudo sysctl -w net.ipv6.conf.${conf_entry}.disable_ipv6=1
done
```

You can re-enable it afterwards, e.g. on Ubuntu
```bash
for conf_entry in all default lo; do
  sudo sysctl -w net.ipv6.conf.${conf_entry}.disable_ipv6=0
done
```
