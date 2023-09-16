# **Bit demo**
Bit demo

React apps and Host apps are in `bit-scope/apps`. Instead the environments are in `bit-scope/envs`.


## **References:**
1. [https://bit.dev/](https://bit.dev/) - Bit Framework Official website
2. [https://bit.cloud/teambit/react/react-env?_gl=1*1e7tbjt*_ga*NjcxNDg0NC4xNjgzMjMwNzI2*_ga_C0T2GH2G99*MTY4MzIzMDcyNS4xLjEuMTY4MzIzMDgwOS40Ni4wLjA.](https://bit.cloud/teambit/react/react-env?_gl=1*1e7tbjt*_ga*NjcxNDg0NC4xNjgzMjMwNzI2*_ga_C0T2GH2G99*MTY4MzIzMDcyNS4xLjEuMTY4MzIzMDgwOS40Ni4wLjA.) - For React environment
3. [https://blog.bitsrc.io/leveraging-microfrontend-architecture-using-bit-components-3cd4d0b1d34e](https://blog.bitsrc.io/leveraging-microfrontend-architecture-using-bit-components-3cd4d0b1d34e) - To create React apps in Bit Framework
4. [https://bit.dev/docs/react-runtime-integration/module-federation/](https://bit.dev/docs/react-runtime-integration/module-federation/) - For Module Federation between React apps and Host app
5. [https://webpack.js.org/concepts/module-federation/#uncaught-error-shared-module-is-not-available-for-eager-consumption](https://webpack.js.org/concepts/module-federation/#uncaught-error-shared-module-is-not-available-for-eager-consumption) - For Module Federation between React apps and Host app
6. [https://dev.to/luistak/cross-micro-frontends-communication-30m3#windowed-observable](https://dev.to/luistak/cross-micro-frontends-communication-30m3#windowed-observable) - For communication between apps
7. **NB:** [https://blog.bitsrc.io/module-federation-vs-single-spa-47da53b67ed0](https://blog.bitsrc.io/module-federation-vs-single-spa-47da53b67ed0) - From this website "when using Module Federation with Angular, React, or Vue JS frameworks, it is important to note that each module must be built using the same framework. This can be a limitation for teams that are using different frameworks within the same application". So with Module Federation, used by Bit Framework, it is not possible to use micro-apps created with different frameworks. This is why I created two React micro-apps and one Host app.
