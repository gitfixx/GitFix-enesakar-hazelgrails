# Hazelcast Plugin for Grails

Update (4/2016): The Hazelcast version has been upgraded to 3.6.2.

### How to Install the Plugin

Just add the following dependency under the dependencies block in your project's build.gradle:

> compile "org.grails.plugins:hazelgrails:1.0.2"

### Configuration

You can configure Hazelcast in detail:

For available options, have a look at:
[http://docs.hazelcast.org/docs/3.6/manual/html-single/index.html#hazelcast-configuration](http://docs.hazelcast.org/docs/3.6/manual/html-single/index.html#hazelcast-configuration)

To use Hazelcast as Hibernate 2nd Level Cache, add the following line to application.groovy:

cache.region.factory_class = 'com.hazelcast.hibernate.HazelcastCacheRegionFactory'

### For More Documentation:
See:
[http://blog.hazelcast.com/distribute-grails-with-hazelcast/](http://blog.hazelcast.com/distribute-grails-with-hazelcast/)

### For a Grails 3 Test Application:
See:
[https://github.com/rohitbishnoi/hazelcast-test](https://github.com/rohitbishnoi/hazelcast-test)