# EFA Linux Kernel Driver Release Notes

## Supported Kernel Versions and Distributions
The driver was tested on the following distributions:

**Amazon Linux:**
* Amazon Linux AMI 2
* Amazon Linux AMI 2018.03
* Amazon Linux AMI 2017.09
* Amazon Linux AMI 2016.09

**CentOS:**
* CentOS 7.4
* CentOS 7.6
* CentOS 7.7

**Red Hat Enterprise Linux:**
* Red Hat Enterprise Linux 7.6

**Ubuntu:**
* Ubuntu 16.04
* Ubuntu 18.04

**SuSE:**
* SuSE 15.1

## r1.5.0 release notes
* RDMA read support
* Make ib_uverbs a soft dependency
* Fix ioctl flows on older kernels
* SuSE 15.1 support

## r1.4.1 release notes
* Fix Incorrect error print
* Add support for CentOS 7.7

## r1.4.0 release notes
* Expose device statistics
* Rate limit admin queue error prints
* Properly assign err variable on everbs device creation failure

## r1.3.1 release notes

* Fix build issue in debian/rules file
* Fix kcompat issue (usage before include)

## r1.3.0 release notes

* Align to the driver that was merged upstream
* Fix a bug where failed functions would return success return value
* Fix modify QP udata check backport
* Fix locking issues in mmap flow
* Add Debian packaging files

## r0.9.2 release notes

* Bug fix module load issue

## r0.9.1 release notes

* Bug fix in EFA spec file
* Upstream review cleanups

## r0.9.0 release notes

Initial commit
