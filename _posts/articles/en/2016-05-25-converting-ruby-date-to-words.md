---
layout: post
title: "Converting ruby date to words"
tagline: "Ruby Gem for converting ruby date into Words. Usefull for those who are get hooked in converting ruby date object into words."
image: /assets/patterns/paisley.png
header:
  image: /assets/patterns/asanoha-400px.png
repository:
  is_project_page: true
  show_downloads: false
  repository_url: http://github.com/nidhinnambiar/date_to_word
tags: ["ruby", "rubygems"]
keywords: ruby, rubygems
ref: rubygems
lang: en
---

[date_to_word](https://rubygems.org/gems/date_to_word) is usefull for those who are got hooked in converting ruby date object into words. While developing an rails application i felt hard to find the methods to get date in words, something like '22/01/1994' as 'Twenty two Janvery Ninteen ninty four'. Which motivated me to write a [gem](https://rubygems.org/gems/date_to_word) that convert ruby date object into words.

## 1.Installation

Add this line to your rails application

```ruby
gem 'date_to_word'
```

then execute bundle

```bash
$ bundle
```
Or install it yourself as:

```bash
$ gem install date_to_word
```


## 2.Usage

You can convert ruby date object into words by just calling

```ruby
DateToWord.date_to_words(<date_object_here>)
```

you can also get only years as 

```ruby
DateToWord.date_to_years(<date_object_here>)
```

Fork the project [here](http://github.com/nidhinnambiar/date_to_word) 
