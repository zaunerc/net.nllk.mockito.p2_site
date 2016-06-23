# net.nllk.mockito.p2_site

As of June 2016 using the `org.hamcrest.core`, `org.mockito.mockito-core` and `org.objenesis` from the Orbit, Eclipse Release or Eclipse Updates P2 sites does not work in an OSGi environment. This project generates a P2 update site of the mentioned bundles with the help of the `p2-maven-plugin`.

The upstream artifacts released on Maven Central are used. Where neccessary modifications to the manifest files of the bundles are applied.

The update site can be found [here](https://dl.bintray.com/zaunerc/p2/net.nllk.mockito.p2_site/).
