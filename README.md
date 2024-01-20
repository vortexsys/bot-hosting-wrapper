# Bot-Hosting.net API Wrapper | Information
Important: Your account token expires every 2 weeks! If something isnt working, make sure you use an up-to-date token :)

A simple API Wrapper for certain informatio in python for bot-hosting.net

This is made by @vortexsys on discord, staff member but not developer of bot-hosting.net

https://github.com/iamkubi/pydactyl Made possible by this guy!
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Change Log](#changelog)
- [License](#license)
- [Contribution](#contributing)
- [Credits](#credits)

## Installation
Dependencies :
- requests
- colorama
- datetime

## Usage
### How to get the Authorization key
Please follow the instructions to get your auth id:
- Login to your account and go to [this page](https://bot-hosting.net/panel/)
- Open your browser's console (usually by pressing F12 or pressing Control + Shift + I)
- Navigate to the 'Console' tab
- Paste in the following code:
```
var token = localStorage.getItem('token');
console.log('Your Auth ID:', token);
```
Now you got your Auth ID and can use all the scripts, congrats!

For an usage of the commands etc. please go [here](https://github.com/vortexsys/bot-hosting-wrapper/wiki/Coding-Usage)

## Changelog
Latest Changelog:
- Updated the way of how it is used
- Tested for optimisation
- Updated/fixed the README file
## License
MIT License

Copyright (c) 2024 Vortex

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

## Contributing
- Follow these simple steps for contributing via [Github](https://github.com/vortexsys/bot-hosting-wrapper)
- Fork the repository.
- Create a new branch: git checkout -b feature/my-feature.
- Commit your changes: git commit -am 'Add my feature'.
- Push to the branch: git push origin feature/my-feature.
- Submit a pull request.

## Credits
Many thanks to:
- @MathiasDPX for giving me some ideas and remaking the code
- @Pondwader for letting me upload this
- @iamkubi for making pydactyl (api wrapper for pterodactyl panel)

Many thanks guys! I appreciate it <3