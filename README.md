# angular-multi-select

Angular multi select component.  Currently used in:
- tester app
- customer app

### Releases
Any updates used by the tester or customer apps should result in a new release.  
- Create a new release version (adhering to semantic versioning rules).
- Add any changes in the version's description
- Update the ChangeLog
- After committing, update your dependent application to point to the new version

### Local Development
The easiest workflow for local development seems to be:
- start working in the app that's going to use the component you're working on
- `bower install` to get the latest version
- make and test your changes directly in the `bower_components/angular-multi-select` folder
- once finished, copy the updated files into your `angular-multi-select` project
- commit and create pull requests for `angular-multi-select` and whatever project is referencing it

### Licence
Released under the MIT license:

The MIT License (MIT)

Copyright (c) 2014-2015 Ignatius Steven (https://github.com/isteven)

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
