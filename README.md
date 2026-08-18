# Native-app Payment Handlers

Native-app Payment Handlers extend the concepts of the [Web-based Payment Handler API](https://w3c.github.io/web-based-payment-handler/), as exposed by the [Payment Request API](https://w3c.github.io/payment-request/), to native applications available on the underlying system. Since specifying native applications is out of scope for the W3C, the actual specification describes only an abstract functional model, which can be implemented by concrete 'app providers' for specific cases. One such case, of Android apps, is also documented in a non-normative technical report.

The specification and technical report are auto-published and can be found:

- [Native-app Payment Handlers specification](https://www.stephenmcgruer.com/native-app-payment-handler/spec.html)
- [Android Payment App Provider technical report](https://www.stephenmcgruer.com/native-app-payment-handler/android-apps.html)

## Building the specification

The specification and technical reports are written using
[bikeshed](https://speced.github.io/bikeshed). To build HTML files from the
sources, install bikeshed and then run:

```
bikeshed spec spec.bs spec.html && \
bikeshed spec android-apps.bs android-apps.html
```

This will create a `*.html` file for each bikeshed file.
