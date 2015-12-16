paper-more-button [![Bower version](https://badge.fury.io/bo/paper-more-button.svg)](http://badge.fury.io/bo/paper-more-button) [![Travis state](https://travis-ci.org/Collaborne/paper-more-button.svg?branch=master)](https://travis-ci.org/Collaborne/paper-more-button)
=========

A material design button to load more items in a list. This element is built for [Polymer 1.x](https://www.polymer-project.org).

![Screenshot](/doc/screenshot.png "Screenshot")


## Properties

Property     | Type    | Description                                    
------------ | ------- | -----------------------------------------------
**has-more** | Boolean | True if the lister has more items than currently shown
**loading**  | Boolean | True if the lister is currently loading items



## Usage

`bower install paper-more-button`

```html
<paper-more-button has-more=[[hasMore]] loading=[[loading]]>More</paper-more-button>
```


## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
    