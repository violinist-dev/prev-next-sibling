# Previous and Next Sibling
[![Build Status](https://travis-ci.org/gordonbanderson/prev-next-sibling.svg?branch=master)](https://travis-ci.org/gordonbanderson/prev-next-sibling)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/gordonbanderson/prev-next-sibling/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/gordonbanderson/prev-next-sibling/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/gordonbanderson/prev-next-sibling/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/gordonbanderson/prev-next-sibling/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/gordonbanderson/prev-next-sibling/badges/build.png?b=master)](https://scrutinizer-ci.com/g/gordonbanderson/prev-next-sibling/build-status/master)
[![codecov.io](https://codecov.io/github/gordonbanderson/prev-next-sibling/coverage.svg?branch=master)](https://codecov.io/github/gordonbanderson/prev-next-sibling?branch=master)

[![Latest Stable Version](https://poser.pugx.org/weboftalent/prevnextsibling/version)](https://packagist.org/packages/weboftalent/prevnextsibling)
[![Latest Unstable Version](https://poser.pugx.org/weboftalent/prevnextsibling/v/unstable)](//packagist.org/packages/weboftalent/prevnextsibling)
[![Total Downloads](https://poser.pugx.org/weboftalent/prevnextsibling/downloads)](https://packagist.org/packages/weboftalent/prevnextsibling)
[![License](https://poser.pugx.org/weboftalent/prevnextsibling/license)](https://packagist.org/packages/weboftalent/prevnextsibling)
[![Monthly Downloads](https://poser.pugx.org/weboftalent/prevnextsibling/d/monthly)](https://packagist.org/packages/weboftalent/prevnextsibling)
[![Daily Downloads](https://poser.pugx.org/weboftalent/prevnextsibling/d/daily)](https://packagist.org/packages/weboftalent/prevnextsibling)

[![Dependency Status](https://www.versioneye.com/php/weboftalent:prevnextsibling/badge.svg)](https://www.versioneye.com/php/weboftalent:prevnextsibling)
[![Reference Status](https://www.versioneye.com/php/weboftalent:prevnextsibling/reference_badge.svg?style=flat)](https://www.versioneye.com/php/weboftalent:prevnextsibling/references)

![codecov.io](https://codecov.io/github/gordonbanderson/prev-next-sibling/branch.svg?branch=master)

## Maintainers

* Gordon Anderson (Nickname: nontgor)
	<gordon.b.anderson@gmail.com>

##Introduction
This module provides convenience methods for previous and next siblings of a
common parent.  It is used for paging through a list of children items.
 
##Installation
```bash
composer require "weboftalent/prev-next-sibling:~1"
```
##Usage
##Previous Sibling
In a template call ``$PreviousSibling``
```
<% with $PreviousSibling %><a href="$Link">$Title</a><% end_with %>
```
If there is no previous sibling the result will be blank and nothing will render.

##NextSibling
In a template call ``$NextSibling``
```
<% with $NextSibling %><a href="$Link">$Title</a><% end_with %>
```
If there is no next sibling the result will be blank and nothing will render.

For more documentation about the module see the provided documentation located
inside the docs folder.

##Requirements
* SilverStripe 3.1 or 3.2
