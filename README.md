# LearnOSM MiddleMan

This is a test of porting Learnosm from Jekyll to [Middleman](http://middlemanapp.com/), a fantastic static site generator written in Ruby. The setup steps are as follows:

**1) Install Dependencies**

Ensure that you have the following installed:
* Ruby (comes pre-installed on Mac)
* Rubygems (comes pre-installed on Mac)
* Bundler (see http://bundler.io for installation instructions)
* middleman-toc (a fork of it installed locally). See:
 * http://bundler.io/git.html)
 * http://tech.bellycard.com/blog/custom-extensions-with-middleman/
 * https://middlemanapp.com/advanced/custom_extensions/

**2) Install Middleman**

```bash
# Run the following commands in the console
gem install middleman
```

For more detailed instructions, see http://middlemanapp.com/basics/getting-started/.

**3) Branches**

* master: a fork of [Franklin](https://github.com/bryanbraun/franklin) that use [middleman-navtree](https://github.com/bryanbraun/middleman-navtree) to generate the TOC.
* middleman-toc: A mix of the previous and [rubymonsters/ruby-for-beginners](https://github.com/rubymonsters/ruby-for-beginners)
