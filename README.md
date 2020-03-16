![Logo](docs/Images/Skoruba-Logo-ReadMe.png)

# React-oidc-client-js

> OpenID Connect (OIDC) client with React and typescript

- This is sample application that contains [oidc-client-js](https://github.com/IdentityModel/oidc-client-js) and `React` with `Typescript`.

- The application is based on `create-react-app` - [Create React App](https://github.com/facebook/create-react-app)

# Project status
[![Build status](https://ci.appveyor.com/api/projects/status/5ml2f07trcm072a1?svg=true)](https://ci.appveyor.com/project/JanSkoruba/react-oidc-client-js)

# Installation

## Cloning app

- `git clone https://github.com/skoruba/react-oidc-client-js.git`
- `cd src/`

## Install dependecies

- Install dependecies - `yarn install`

## Running app

- `yarn start` - start the web server that is running on [http://localhost:4200](http://localhost:4200)

- The application is connected to `OpenID Connect Provider` that is running on [https://demo.identityserver.io/](https://demo.identityserver.io/)
- This STS has configured a SPA client to run on http://localhost:4200, therefore a sample application will be running on this port `4200`.

## App preview

![Logo](docs/Images/react-oidc-client-screenshot.png)



```
<Resource context="(.*)/oauth2/oidcdiscovery/(.*)" secured="false" http-method="GET"/>
```
```

    <filter>
        <filter-name>CORS</filter-name>
        <filter-class>com.thetransactioncompany.cors.CORSFilter</filter-class>
        <init-param>
            <param-name>cors.allowOrigin</param-name>
            <param-value>http://localhost:3000</param-value>
        </init-param>
    </filter>
    
    
    <filter-mapping>
        <filter-name>CORS</filter-name>
        <url-pattern>/*</url-pattern>
    </filter-mapping>

    <filter>
        <filter-name>HttpHeaderSecurityFilter</filter-name>
        <filter-class>org.apache.catalina.filters.HttpHeaderSecurityFilter</filter-class>
        <init-param>
            <param-name>hstsEnabled</param-name>
            <param-value>false</param-value>
        </init-param>
    </filter>
```
