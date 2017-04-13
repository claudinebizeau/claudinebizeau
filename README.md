# rmail
RMail | The global standard for secure & certified electronic communications

This is a work-in-progress and not yet ready for production.

## Test Registered Email messages
To test, deploy on a Zimbra server, and use a persona that is known and
activated in RMail, then compose an email and hit the RPost button in the
compose window.

## Test register new rmail account
Also, you can create/register new accounts, using the zimlet panel menu 
(left bottom).

## Configure server

    zmprov mcf +zimbraCustomMimeHeaderNameAllowed X-RPost-Type
    zmprov mcf +zimbraCustomMimeHeaderNameAllowed X-RPost-App

## MIT License

Copyright (c) 2017 Zeta Alliance

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
