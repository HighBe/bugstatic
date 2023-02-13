Centos
|num|id|summery|remark|
|----|----|----|----|
|1|[2020369](https://bugzilla.redhat.com/show_bug.cgi?id=2020369)| type confusion vulnerability can lead to a bypass of CVE-2020-7709 when the pointer components are arrays|  |
|2|[2041833](https://bugzilla.redhat.com/show_bug.cgi?id=2041833)|type confusion vulnerability can lead to a bypass of CVE-2020-28477| The === operator (strict equality operator) returns false if the operands have different type.| 
<br>

Coreutils
|num|summery|remark|
|----|----|----|
|[1](http://git.savannah.gnu.org/gitweb/?p=coreutils.git;a=commit;h=e94d95075dd919e5e6ec0c8ed09477e58b863788)| improve integer overflow checking|Prefer signed to unsigned types  |
<br>

OpenSSH
|num|id|summery|remark|
|----|----|----|----|
|1|[3190](https://bugzilla.mindrot.org/show_bug.cgi?id=3190)| Inconsistent handling of private keys without accompanying public keys|  |
|2|[2389](https://bugzilla.mindrot.org/show_bug.cgi?id=2389)| update the PROTOCOL.certkeys spec to avoid confusion regarding encoding of critical options fields|  |
|3|[3253](https://bugzilla.mindrot.org/show_bug.cgi?id=3253)| ssh-keygen man page still lists deprecated key types for -t| update the list of available values after -t in ssh-keygen.1. |
<br>

CVE(Common Vulnerabilities & Exposures)
<br>
type conversion
|num|id|description|software|
|----|----|----|----|
|1|[CVE-2022-3979](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-3979)| The manipulation of the argument hash leads to incorrect type conversion.|NagVis|
|2|[CVE-2022-29209](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-29209)| have an incorrect logic when comparing `size_t` and `int` values.|TensorFlow|
|3|[CVE-2021-41202](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-41202)| Due to C++ implicit conversion rules, both branches of the condition will be cast to `double`|TensorFlow|
|4|[CVE-2021-37645](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-37645)| an integer overflow issue caused by converting a signed integer value to an unsigned one|TensorFlow|
|5|[CVE-2021-36357](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-36357)| a type mismatch that can truncate a higher integer value to a smaller one|OpenPOWER|
|6|[CVE-2021-29513](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-29513)| Calling TF operations with tensors of non-numeric types when the operations expect numeric tensors result in null pointer dereferences.|TensorFlow|
|7|[CVE-2017-7961](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-7961)| outside the range of representable values of type long| |
|8|[CVE-2014-9515](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2014-9515)| Dozer improperly uses a reflection-based approach to type conversion|Dozer|
|9|[CVE-2013-1802](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2013-1802)|not properly restrict casts of string values, which might allow remote attackers to conduct object-injection attacks and execute arbitrary code|extlib gem|
|10|[CVE-2013-1801](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2013-1801)| not properly restrict casts of string values, which might allow remote attackers to conduct object-injection attacks and execute arbitrary code|httparty gem|
|11|[CVE-2013-1800](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2013-1800)| not properly restrict casts of string values, which might allow remote attackers to conduct object-injection attacks and execute arbitrary code|crack gem|
|12|[CVE-2013-0175](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2013-0175)| does not properly restrict casts of string values, which allows remote attackers to conduct object-injection attacks and execute arbitrary code|multi_xml gem|
<br>

type casting
|num|id|description|software|
|----|----|----|----|
|1|[CVE-2016-5862](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-5862)| 	When a control related to codec is issued from userspace in all Qualcomm products, the type casting is done to the container structure instead of the codec's individual structure, resulting in a device restart after kernel crash occurs.|Qualcomm|
|2|[CVE-2016-1000004](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-1000004)| Insufficient type checks were employed prior to casting input data in SimpleXMLElement_exportNode and simplexml_import_dom.|HHVM|
<br>

type coercion
|num|id|description|software|
|----|----|----|----|
|1|[CVE-2021-41272](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-41272)| Starting in version 21.10.0, changes in the implementation of the SHL, SHR, and SAR operations resulted in the introduction of a signed type coercion error in values that represent negative values for 32 bit signed integers. |Besu|
<br>

type juggling
|num|id|description|software|
|----|----|----|----|
|1|[CVE-2021-40693](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-40693)| An authentication bypass risk was identified in the external database authentication functionality, due to a type juggling vulnerability.| |
|2|[CVE-2020-23361](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-23361)| phpList 3.5.3 allows type juggling for login bypass because == is used instead of === for password hashes, which mishandles hashes that begin with 0e followed by exclusively numerical characters.|phpList|
|3|[CVE-2020-23356](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-23356)| dmin/kernel/api/login.class.phpin in nibbleblog v3.7.1c allows type juggling for login bypass because == is used instead of === for password hashes, which mishandles hashes that begin with 0e followed by exclusively numerical characters.|nibbleblog|
|4|[CVE-2019-14537](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-14537)|YOURLS through 1.7.3 is affected by a type juggling vulnerability in the api component that can result in login bypass.|YOURLS|
|5|[CVE-2019-10231](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-10231)|Teclib GLPI before 9.4.1.1 is affected by a PHP type juggling vulnerability allowing bypass of authentication. This occurs in Auth::checkPassword() (inc/auth.class.php).|GLPI|
|6|[CVE-2017-1001000](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-1001000)|The register_routes function does not require an integer identifier, which allows remote attackers to modify arbitrary pages via a request for wp-json/wp/v2/posts followed by a numeric value and a non-numeric value, as demonstrated by the wp-json/wp/v2/posts/123?id=123helloworld URI.|WordPress|
<br>


lighttpd
|num|id|description|
|---|---|---|
|1|[627](https://redmine.lighttpd.net/issues/627)| casting pointer types for variebyte data is somewhat careless|
<br>

FreeBSD  搜索可能有问题，有的关键词第一次搜索的时候有结果，第二次搜索的时候就没有内容了。可能有部分内容没有搜索到
|num|id|summary|
|---|---|---|
|1|[181840](https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=181840)|error: incompatible integer to pointer conversion passing 'unsigned long long' to parameter of type 'cap_rights_t *' (aka 'struct cap_rights *')|
|2|[190126](https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=190126)|error: incompatible integer to pointer conversion passing 'unsigned long long' to parameter of type 'cap_rights_t *' (aka 'struct cap_rights *')|
<br>

postfix VSFTP OpenSolaris没找到
<br>
linux的bug页面无法打开：landfill.bugzilla.org/bugzilla-tip/query.cgi 
<br>
WineHQ 没有符合条件的内容:https://bugs.winehq.org/buglist.cgi?quicksearch=type%20conversion



