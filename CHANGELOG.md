Release v0.5.1
* Update examples/README ([#317](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/317), @otterley)
* Changelog gen ([#318](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/318), @nckturner)
* Fix CRD mapper blocking all others because caches never sync  and revamp backend-mode flag ([#303](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/303), @wongma7)
* Update aws-sdk-go to version v1.30.0 ([#306](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/306), @nckturner)
* Bump k8s.io/ dependencies to 1.16.8 ([#305](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/305), @wongma7)
* chown aws-iam-authenticator to avoid permission denied ([#302](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/302), @wongma7)
* Indentation and unit test improvements ([#298](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/298), @bhagwat070919)
* Adding Rate limiting ec2:DescribeInstances API along with Batching for high TPS ([#292](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/292), @bhagwat070919)
* Restrict ClusterRole to readonly IAMIdentityMapping access ([#287](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/287), @rifelpet)
* added selector to spec and changed from extenstions to apps/v1 ([#291](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/291), @andarob)
* Add AWS AccessKeyID as an extra field in UserInfo ([#286](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/286), @pepov)
* Allow server port customization ([#278](https://github.com/kubernetes-sigs/aws-iam-authenticator/pull/278), @diversario)
