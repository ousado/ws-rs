<a name="v0.4.6"></a>
### v0.4.6 (2016-03-17)

#### Bug Fixes

*   Debug check failing when http handshake fails ([fb84fb32](fb84fb32))

#### Features
* **ssl:** Re-enable support for SSL in Windows ([536779e9](536779e9))



<a name="v0.4.5"></a>
### v0.4.5 (2016-02-18)


#### Bug Fixes

*   Handle http parse errors gracefully, closes #28 ([fd40ab7c](fd40ab7c))
*   Failure to reply to http connection, close #29 ([d3ada6ad](d3ada6ad))
* **io:**  Type mismatch when not building will +ssl ([258754bd](258754bd))

#### Features

*   Add connection_lost method to factory ([9d057dc5](9d057dc5))
* **ssl:**  Try multiple addresses for ssl connections too ([e5db833b](e5db833b))



<a name="v0.4.4"></a>
### v0.4.4 (2016-02-10)


#### Bug Fixes

*   Trigger on_close when connection hangs up. Fix #25 ([2568e148](2568e148))


<a name="0.4.3"></a>
### v0.4.3 (2015-12-20)


#### Bug Fixes

* **frame:**  Fail to compile on 32bit, close #20 ([c78197d0](c78197d0))

#### Features

* **util:**
  *  Add rexports of mio utilities to facilitate timeouts ([75a4baa4](75a4baa4))
  *  Support custom timeout events. ([8d463c9e](8d463c9e))



<a name="0.4.2"></a>
### v0.4.2 (2015-12-14)


#### Features

* **protocol:**  Publicize OpCode for easier frame management ([c6ef6e7f](c6ef6e7f))
* **ssl:**
  *  Make ssl support optional ([82c99e64](82c99e64))
  *  Don't support ssl on Windows #12 ([0047ce8e](0047ce8e))

#### Documentation

*   Add ping/pong low-level frame access example ([3d4d994](3d4d994)


<a name="0.4.1"></a>
### v0.4.1 (2015-12-08)


#### Features

* **frame:**  publicize Frame struct ([2ba15de2](2ba15de2))


<a name="0.4.0"></a>
### v0.4.0 (2015-12-02)


#### Features

*   Add support for SSL (wss) connections ([c4947a5](c4947a5))

<a name="0.3.1"></a>
## 0.3.1 (2015-11-10)


#### Bug Fixes

* **io:** check remote_addr after socket is readable ([b6cccbb3](b6cccbb3))

#### Features

* **handshake:**  Add remote_addr method on Handshake ([23b83d2f](23b83d2f))


<a name="0.3.0"></a>
### v0.3.0 (2015-11-02)


#### Documentation

*   Add bench server example using settings ([7a0de0a](7a0de0a))

#### Features

*   Try multiple addresses in clients ([ec99a7a](ec99a7a))
*   Improved Settings ([a67951f](a67951f))
*   Add broadcast sender to WebSocket struct ([a0af1df](a0af1df))
*   Add is_empty method to message. ([6c99167f](6c99167f))

<a name="0.2.1"></a>
### v0.2.1 (2015-09-26)


#### Documentation

*   Add a [command line example](https://github.com/housleyjk/ws-rs/blob/9fcafa19f974cf72581460a1e9f3b27e7201cd24/examples/cli.rs)

#### Bug Fixes

*   Don't use absolute URI in client handshake request. Fixes [#1](https://github.com/housleyjk/ws-rs/issues/1)

<a name="0.2.0"></a>
### v0.2.0 (2015-09-16)


#### Features

*   Add settings ([366e2e0](366e2e0))


<a name="0.1.0"></a>
### v0.1.0 (2015-08-28)
Initial Release
