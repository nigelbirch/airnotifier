## Introduction
AirNotifier is a REST server for apple push notification service.
APNs allows provider to do peer-to-peer communication, if notification is from other provider other than master provider, we need a push notification forwarder, AirNotifier comes to rescue.

## Status
Under heavy development

## Design
- [Product design](https://github.com/dongsheng/airnotifier/wiki/Specification)

## Features
- Restful API allows providers to send notification through straightforward restful interface
- Non-blocking API design allows master provider to handle large loads of request smoothly
- Logging usage
- OAuth, providers apply OAuth key and secret from master provider

## Requirements

### Server stack
- [Python 2.7+](http://www.python.org)
- [Tornado](http://tornadoweb.org)
- [MongoDB](http://www.mongodb.org)

## Copyright
Copyright (c) 2012, Dongsheng Cai

## License

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

    * Redistributions of source code must retain the above copyright
      notice, this list of conditions and the following disclaimer.
    * Redistributions in binary form must reproduce the above copyright
      notice, this list of conditions and the following disclaimer in the
      documentation and/or other materials provided with the distribution.
    * Neither the name of the Dongsheng Cai nor the names of its 
      contributors may be used to endorse or promote products derived
      from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL DONGSHENG CAI BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
