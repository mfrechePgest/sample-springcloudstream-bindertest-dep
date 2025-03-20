# sample-springcloudstream-bindertest-dep

Simple repo that illustrate dependency problem in new Spring Cloud release

Just run the simple `SpringcloudstreamBindertestDepApplicationTests.contextLoads` unit test will fail
`gradle dependencies` will show the problem with double micrometer bridge (brave & otel)

Related issue : [Spring Cloud Stream #3100](https://github.com/spring-cloud/spring-cloud-stream/issues/3100)
