# OmniAuth Hootsuite

This is an OmniAuth strategy for authenticating with Hootsuite.

At the time of writing, you need to apply for a developer account here: https://hootsuite.com/developers/new-app

Then you must contact developer support to add REST API credentials and setup a callback url.

## Basic Usage

    use OmniAuth::Builder do
      provider :hootsuite, ENV['HOOTSUITE_REST_API_CLIENT_ID'], ENV['HOOTSUITE_REST_API_SECRET']
    end

## License

Copyright (c) 2017 Grafly, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
