
### Changelog

#### v5.x
* python3 only, tested on 3.10 but earlier versions 'should' work ok
* buildable via 'poetry'
* installable via 'pip'
* removed threading for supportability reasons
* Added ability to write directly to influxdb v2

#### v4.x
* Added ability to write directly to influxdb
* Threading cleanup

#### v3.x
* Multiple Air/Sky devices per hub is now supported.  See the -M option below
* The --weewx option has been deleted

#### v2.x
* The listener now supports python3. All examples below have been updated accordingly.
* Typical output has been significantly quieted down, with debugging output suppressed unless you use the --verbose flag

