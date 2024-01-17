
### Changelog

Dates are the first tagged versions in GitHub, which might be pre-releases.

#### v5.x (2023-01-27)

Functionality:
* Added ability to write directly to influxdb v2
* Added a --quiet option to output just the formatted data
* removed threading for supportability reasons
* do a little more simulating in the simulator
* use my station id by default in the simulator

Packaging:
* python3 only, tested on 3.10 but earlier versions 'should' work ok
* buildable via 'poetry'
* installable via 'pip'

#### v4.x (2020-01-05)
* Added ability to write directly to influxdb
* Threading cleanup

#### v3.x (2019-07-13)
* Multiple Air/Sky devices per hub is now supported.  See the -M option below
* The --weewx option has been deleted

#### v2.x (2019-02-20)
* The listener now supports python3. All examples below have been updated accordingly.
* Typical output has been significantly quieted down, with debugging output suppressed unless you use the --verbose flag

#### v1.x (2018-09-24)
* original releases for python2
