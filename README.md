# HTML Refactoring

* [Installation](#installation)
* [Usage](#usage)
* [Changes](#changes)
* [License](#license)

## Installation

Simply go to the link - https://symoxn7.github.io/html-refactoring/#search-engine-optimization

## Usage

This webpage is to provide information on what services and benefits Horiseon can provided to potential customers.
The top bar will include 3 links that clicking will take you to the relevant sections, these sections provide further information on the services. The right bar shows the benefits of working with Horiseon.

## Changes

### HTML Changes:
1. Changed all div to section
2. Added alt to all img lines
3. Changed line 29 from class= to id= - this was preventing the link from working
4. Changed line 12 and 27 from section to header
5. Changed line 31 and 53 from section to nav
6. Changed line 55 and 77 from section to aside


### CCS Changes:
1. Renamed .header div to .header section
2. Renamed .header div ul to .header section ul
3. Renamed .header div ul li to .header section ul li
4. Consolidated CCS classes .benefit-lead, .benefit-brand & .benefit-cost into .benefit
5. Consolidated CCS classes .benefit-lead h3, .benefit-brand h3, .benefit-cost h3 into .benefit h3
6. Consolidated CCS classes .benefit-lead img, .benefit-brand img, .benefit-cost img into .benefit img
7. Consolidated CCS classes .search-engine-optimization, .online-reputation-management, .social-media-marketing into .services
8. Consolidated CCS classes .search-engine-optimization img, .online-reputation-management img, .social-media-marketing img into .services img
9. Consolidated CCS classes .search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2 into .services h2

Background image:

![digital-marketing-meeting](./assets/images/digital-marketing-meeting.jpg)

Main contenct images:

![social-media-marketing](./assets/images/social-media-marketing.jpg)
![search-engine-optimization](./assets/images/search-engine-optimization.jpg)
![online-reputation-management](./assets/images/online-reputation-management.jpg)

## License

MIT License

Copyright (c) 2023 Symox

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
