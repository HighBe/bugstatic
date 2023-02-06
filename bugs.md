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
|3|[3253](https://bugzilla.mindrot.org/show_bug.cgi?id=3253)| ssh-keygen man page still lists deprecated key types for -t| pdate the list of available values after -t in ssh-keygen.1. |
