# Changelog

## 2020-01-20
* Adding Oracle Linux `8.1` images for both `amd64` and `arm64v8`
* Updating `8-slim` image
* Retain `tzdata` database across all images
* https://github.com/docker-library/official-images/pull/7302

## 2019-12-24
* Updated Oracle Linux `6, 6.10, 6-slim, 7, 7.7` and `7-slim` images for `arm64v8`
* https://github.com/docker-library/official-images/pull/7192

## 2019-12-20
* Updated Oracle Linux `6, 6.10, 6-slim, 7, 7.7` and `7-slim` images for `amd64`
* https://github.com/docker-library/official-images/pull/7177

## 2019-11-19
* **Breaking changes:**
  * Update `dist-amd64/8-slim` image to use `microdnf` to reduce the image size
  * Update `dist-arm64v8/8-slim` image to use `microdnf` to reduce the image size
* Update `dist-amd64/7-slim` image for `sudo-1.8.23-4.0.1.el7.src.rpm`
* Update `dist-arm64v8/7-slim` image for `sudo-1.8.23-4.0.1.el7.src.rpm`
* Added `dist-amd64/7.7` image and assigned it the `7, latest` tags
* Added `dist-arm64v8/7.7` image and assigned it the `7, latest` tags
* https://github.com/docker-library/official-images/pull/7001

## 2019-10-16
* **Breaking change:** `python36` removed from `8-slim` image
* Several other packages that had been included via dependencies were removed
* https://github.com/docker-library/official-images/pull/6784

## 2019-08-09
* Updated Oracle Linux `7.6`, `7-slim`, `8.0` and `8-slim` for `curl`
* https://github.com/docker-library/official-images/pull/6428

## 2019-07-30
* Reduced the size of the `8-slim` image for `amd64` and `arm64v8`
* https://github.com/docker-library/official-images/pull/6365
* https://github.com/docker-library/official-images/pull/6380

## 2019-07-20
* Added Oracle Linux 8 for `amd64` and `arm64v8`
* https://github.com/docker-library/official-images/pull/6327

## 2019-07-16
* Update Oracle Linux `6.10` for `dbus`
* https://github.com/docker-library/official-images/pull/6297

## 2019-07-02
* Update Oracle Linux `7.6` on `amd64` and `arm64v8` for `vim`
* https://github.com/docker-library/official-images/pull/6208

## 2019-06-24
* Update Oracle Linux `7.6` and `7-slim` on `amd64` and `arm64v8` for Python 2.7
* https://github.com/docker-library/official-images/pull/6148

## 2019-06-14
* Update Oracle Linux `6` and `6-slim` on `amd64` for Python 2.6
* https://github.com/docker-library/official-images/pull/6081

## 2019-05-31
* Update Oracle Linux `7.6` on `amd64` and `arm64v8` for `bind`
* https://github.com/docker-library/official-images/pull/5996

## 2019-04-11
* Update Oracle Linux `6.10` on `amd64` and `7.6`, `7-slim` on `amd64` and `arm64v8` for OpenSSH and `python` 
* https://github.com/docker-library/official-images/pull/5715

## 2019-03-29
* Update Oracle Linux `7.6` and `7-slim` on `amd64` for `libssh2`
* https://github.com/docker-library/official-images/pull/5631

## 2019-03-15
* Update Oracle Linux `7.6` and `7-slim` on `amd64` and `arm64v8` for OpenSSL
* https://github.com/docker-library/official-images/pull/5547

## 2019-02-20
* Update Oracle Linux `7.6` on `amd64` and `arm64v8` for `systemd`
* https://github.com/docker-library/official-images/pull/5456

## 2019-01-31
* Update Oracle Linux `7.6` on `amd64` and `arm64v8` for `systemd`
* https://github.com/docker-library/official-images/pull/5376

## 2019-01-15
* Update Oracle Linux `7.6` on `amd64` and `arm64v8` for `systemd`
* https://github.com/docker-library/official-images/pull/5292

## 2018-11-08
* Added Oracle Linux 7 Update 6 for `amd64` and `arm64v8`
* https://github.com/docker-library/official-images/pull/5044

## 2018-10-16
* Update Oracle Linux `6.10`, `6-slim`, `7.5`, `7-slim` on `amd64` for OpenSSL
* https://github.com/docker-library/official-images/pull/4957

## 2018-10-10
* Update Oracle Linux `6.10` and `6-slim` on `amd64` for NSS
* https://github.com/docker-library/official-images/pull/4931

## 2018-09-27
* Update Oracle Linux `7.5` and `7-slim` on `amd64` and `arm64v8` for NSS
* https://github.com/docker-library/official-images/pull/4887

## 2018-08-28
* Update Oracle Linux 7 Update 5 for `bind`
* https://github.com/docker-library/official-images/pull/4783

## 2018-08-03
* Updated `yum-utils` on Oracle Linux 6 and 7
* https://github.com/docker-library/official-images/pull/4677

## 2018-07-26
* Updating Oracle Linux 6 and 7 images for `amd64`/`arm64v8` to resolve CVE-2018-12020
* https://github.com/docker-library/official-images/pull/4636

## 2018-07-07
* Added Oracle Linux 6 Update 10 for `amd64`
* Added Oracle Linux 7 Update 5 for `arm64v8`
* https://github.com/docker-library/official-images/pull/4545

## 2018-06-02
* Update `oraclelinux:6.9` for `procps`
* https://github.com/docker-library/official-images/pull/4414

## 2018-05-25
* Update `oraclelinux:7.5` for `procps-ng` update
* https://github.com/docker-library/official-images/pull/4389

## 2018-05-16
* Update Oracle Linux 6 and 7 `amd64` images with `dhcp` updates
* https://github.com/docker-library/official-images/pull/4363

## 2018-04-18
* Added Oracle Linux 7 Update 5 for `amd64` and `arm64v8`
* https://github.com/docker-library/official-images/pull/4258

## 2018-03-21
* Added `arm64v8` builds for Oracle Linux 7
* https://github.com/docker-library/official-images/pull/4149

## 2018-03-13
* Updating `dhcp` on Oracle Linux 7 for CVE-2018-5732 and CVE-2018-5733 
* https://github.com/docker-library/official-images/pull/4119

## 2018-03-09
* Updating the `oraclelinux:6.9` image to address CVE-2018-5732 and CVE-2018-5733
* https://github.com/docker-library/official-images/pull/4109

## 2018-01-01
* Updating `oraclelinux:7.4` to resolve CVE-2018-1049
* https://github.com/docker-library/official-images/pull/3963

## 2018-01-23
* Updating `oraclelinux:7.4` for CVE-2017-3145
* https://github.com/docker-library/official-images/pull/3925

## 2017-11-29
* Updating Oracle Linux `7.4` and `7-slim` images to resolve CVE-2017-1000257
* https://github.com/docker-library/official-images/pull/3749

## 2017-09-30
* Updating `6.9`, `6-slim`, `7.4`, `7-slim` to address CVE-2017-7805
* https://github.com/docker-library/official-images/pull/3518

## 2017-09-01
* Updating Oracle Linux 6 Update 9 for CVE-2016-6210
* https://github.com/docker-library/official-images/pull/3399

## 2017-08-09
* Added Oracle Linux 7 Update 4
* https://github.com/docker-library/official-images/pull/3293

## 2017-07-07
* Updating Oracle Linux 7 Update 3 to resolve CVE-2017-3142 and CVE-2017-3142
* https://github.com/docker-library/official-images/pull/3151

## 2017-06-21
* Updated `6.9`, `6-slim`, `7.3`, `7-slim` images for CVE-2017-1000366 (Stack Clash)
* https://github.com/docker-library/official-images/pull/3103

## 2017-05-31
* Updating Oracle Linux 6 and 7 images for CVE-2017-7502
* https://github.com/docker-library/official-images/pull/2996

## 2017-04-21
* Update Oracle Linux images with CVE fixes
  * CVE-2017-3136
  * CVE-2017-3137
* https://github.com/docker-library/official-images/pull/2878

## 2017-04-13
* Updating Oracle Linux 7 Update 3 for CVE-2017-2616
* https://github.com/docker-library/official-images/pull/2855

## 2017-03-30
* Updating Oracle Linux 6 images to resolve CVE-2017-2628 
* https://github.com/docker-library/official-images/pull/2797

## 2017-03-19
* Adding Oracle Linux 6 Update 9 and updating the `6-slim` image accordingly
* This also changed the `6` tag to point to `6.9`
* https://github.com/docker-library/official-images/pull/2793

## 2017-02-22
* Updating the Oracle Linux 6 and 7 (full/slim) images to address the following OpenSSL CVEs:
  * CVE-2017-3731 - DoS via truncated packets with RC4-MD5 cipher
  * CVE-2016-8610 - DoS of single-threaded servers via excessive alerts
* https://github.com/docker-library/official-images/pull/2680

## 2017-02-17
* Size reductions on `6.8`, `6` and `6-slim` images
* https://github.com/docker-library/official-images/pull/2665

## 2017-02-16
* Updated Oracle Linux 7 image for CVE-2017-3135
* Added `oraclelinux:7-slim` and `oraclelinux:6-slim` images
* https://github.com/docker-library/official-images/pull/2660

## 2017-01-18
* Updating Oracle Linux 7 Update 3 image for bind CVE fixes
* https://github.com/docker-library/official-images/pull/2541

## 2016-12-23
* Updated Oracle Linux 6 Update 8 and 7 Update 3 images for CVE-2016-1248
* https://github.com/docker-library/official-images/pull/2480

## 2016-11-30
* Updated Oracle Linux 6 Update 8 and 7 Update 3 to address CVE-2016-0718
* https://github.com/docker-library/official-images/pull/2405

## 2016-11-22
* Updating Oracle Linux 5, Oracle Linux 6 and Oracle Linux 7 images for CVE updates
  * CVE-2016-2834
  * CVE-2016-5285
  * CVE-2016-8635
* https://github.com/docker-library/official-images/pull/2379

## 2016-11-17
* Updated Oracle Linux 7 Update 3 for CVE-2016-7545
* https://github.com/docker-library/official-images/pull/2357

## 2016-11-16
* Updated Oracle Linux 6 Update 8 for CVE-2016-7545
* https://github.com/docker-library/official-images/pull/2352

## 2016-11-11
* Adding Oracle Linux 7 Update 3 and updating the `7` and `latest` tags
* https://github.com/docker-library/official-images/pull/2335

## 2016-11-09
* Updated Oracle Linux 6 Update 8 image to patch CVE-2016-6313 
  * fix CVE-2016-6313 - predictable PRNG output (#1366105)
* https://github.com/docker-library/official-images/pull/2328

## 2016-10-26
* Updated Oracle Linux 7 Update 2/latest image/tag with updates for some CVEs
  * CVE-2016-2776
* Updated `tzdata` and `curl`
* https://github.com/docker-library/official-images/pull/2282

## 2016-10-18
* Updated Oracle Linux 5 for OpenSSL CVEs
  * CVE-2016-2177
  * CVE-2016-2178
  * CVE-2016-2179
  * CVE-2016-2180
  * CVE-2016-2181
  * CVE-2016-2182
  * CVE-2016-2183
  * CVE-2016-6302
  * CVE-2016-6303
  * CVE-2016-6304
  * CVE-2016-6305
  * CVE-2016-6306
  * CVE-2016-6307
  * CVE-2016-6308
* https://github.com/docker-library/official-images/pull/2262

## 2016-09-29
* Updated Oracle Linux 6 and 7 for OpenSSL CVEs
  * CVE-2016-2177
  * CVE-2016-2178
  * CVE-2016-2179
  * CVE-2016-2180
  * CVE-2016-2181
  * CVE-2016-2182
  * CVE-2016-2183
  * CVE-2016-6302
  * CVE-2016-6303
  * CVE-2016-6304
  * CVE-2016-6305
  * CVE-2016-6306
  * CVE-2016-6307
  * CVE-2016-6308
* https://github.com/docker-library/official-images/pull/2203

## 2016-07-20
* Addresses moby/moby#10180 by including yum-plugin-ovl in the base image.
* https://github.com/docker-library/official-images/pull/1963

## 2016-06-23
* Address some OpenSSL CVEs in the new Oracle Linux 5 image
  * CVE-2016-0799
  * CVE-2016-2105
  * CVE-2016-2106
  * CVE-2016-2109
* Added the `yum-utils` package to the base filesystem install for Oracle Linux 6 and Oracle Linux 7.
* https://github.com/docker-library/official-images/pull/1871

## 2016-06-03
* Updated Oracle Linux 5 image with OpenSSL CVE fixes
* https://github.com/docker-library/official-images/pull/1804

## 2016-05-21
* Add Oracle Linux 6 Update 8 and update the `6` tag accordingly
* This also updates `oraclelinux:6` to point to `6.8`.
* https://github.com/docker-library/official-images/pull/1760
* https://github.com/docker-library/official-images/pull/1761

## 2016-05-13
* Updated Oracle Linux 6 Update 7 to fix OpenSSL CVEs
  * CVE-2016-2105
  * CVE-2016-2106
  * CVE-2016-2107
  * CVE-2016-2108
  * CVE-2016-2109
  * CVE-2016-2176
* https://github.com/docker-library/official-images/pull/1732

## 2016-05-10
* Updated Oracle Linux 7 Update 2 base image to address OpenSSL CVEs
  * CVE-2016-2105
  * CVE-2016-2106
  * CVE-2016-2107
  * CVE-2016-2108
  * CVE-2016-2109
  * CVE-2016-2176
* https://github.com/docker-library/official-images/pull/1722

## 2016-03-03
* Updated Oracle Linux to address OpenSSL CVEs
  * CVE-2016-0800 ("DROWN")
  * CVE-2016-0799
  * CVE-2016-0798
  * CVE-2016-0797
  * CVE-2016-0705
  * CVE-2016-0704 
  * CVE-2016-0703
  * CVE-2016-0702 ("Cache Bleed")
* https://github.com/docker-library/official-images/pull/1508

## 2016-02-17
* Updated Oracle Linux 7 Update 2 and 6 Update 7 images to resolve CVE-2015-7547
* https://github.com/docker-library/official-images/pull/1453

## 2015-12-18
* Updated Oracle Linux 7 Update 2 image to resolve the following CVEs:
  * CVE-2015-3193
  * CVE-2015-3194
  * CVE-2015-3195 
  * CVE-2015-3196
* https://github.com/docker-library/official-images/pull/1287

## 2015-12-02
* Add Oracle Linux 7 Update 2
* https://github.com/docker-library/official-images/pull/1228

## 2015-09-17
* Tiny update to the base Oracle Linux 7 image to include Oracle-specific RPM macros for build purposes. 
* This change was already made to the Oracle Linux 6 image.
* https://github.com/docker-library/official-images/pull/1059

## 2015-06-30
* Adding Oracle Linux 6 Update 7
* https://github.com/docker-library/official-images/pull/935

## 2015-06-11
* Updated images to support upstream Docker Engine RPM builds on Oracle Linux 6.
* https://github.com/docker-library/official-images/pull/886

## 2015-06-16
* Updated Oracle Linux 6 Update 6 and 7 Update 1 images with new OpenSSL CVE fixes to address the LOGJAM (CVE-2015-4000) as well as:
  * improved fix for CVE-2015-1791
  * add missing parts of CVE-2015-0209 fix for correctness although unexploitable
  * fix CVE-2014-8176 - invalid free in DTLS buffering code
  * fix CVE-2015-1789 - out-of-bounds read in X509_cmp_time
  * fix CVE-2015-1790 - PKCS7 crash with missing EncryptedContent
  * fix CVE-2015-1791 - race condition handling NewSessionTicket
  * fix CVE-2015-1792 - CMS verify infinite loop with unknown hash function
  * fix CVE-2015-3216 - regression in RAND locking that can cause segfaults on read in multithreaded applications
* https://github.com/docker-library/official-images/pull/822

## 2015-03-25
* Updated Oracle Linux images with latest OpenSSL CVE fixes:
  * fix CVE-2015-0209 - potential use after free in d2i_ECPrivateKey()
  * fix CVE-2015-0286 - improper handling of ASN.1 boolean comparison
  * fix CVE-2015-0287 - ASN.1 structure reuse decoding memory corruption
  * fix CVE-2015-0289 - NULL dereference decoding invalid PKCS#7 data
  * fix CVE-2015-0292 - integer underflow in base64 decoder
  * fix CVE-2015-0293 - triggerable assert in SSLv2 server
* https://github.com/docker-library/official-images/pull/618

## 2015-03-19
* Added Oracle Linux 7 Update 1
* Also switched the `oraclelinux:latest` and `oraclelinux:7` tags to 7.1.
* https://github.com/docker-library/official-images/pull/568

## 2015-02-11
* All three images are set to UTC and we have added Oracle Linux 5 Update 11 (includes GHOST vulnerability fix).
* https://github.com/docker-library/official-images/pull/481

## 2015-02-05
* Updated Oracle Linux images that resolve CVE-2015-0235 (glibc update)
* https://github.com/docker-library/official-images/pull/457

## 2014-12-25
* Initial submission of Oracle Linux 6 Update 5
* 6.5 and 7.0 as official images on Docker Hub
* https://github.com/docker-library/official-images/pull/372