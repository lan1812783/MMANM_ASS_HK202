# MMANM_ASS_HK202

## Run SampleAcn
In terminal, navigate to `src` directory, compile `SampleAcn.java`, `SampleLoginModule.java`, and `SamplePrincipal.java`:
```
javac sample/SampleAcn.java sample/module/SampleLoginModule.java sample/principal/SamplePrincipal.java
```
Execute the SampleAcn application:
```
-Djava.security.auth.login.config==sample_jaas.config that the login configuration file to be used is sample_jaas.config.
```

## References
[JAAS Authentication Tutorial](https://docs.oracle.com/en/java/javase/15/security/jaas-authentication-tutorial.html#GUID-BFEBDB00-9826-499C-A20F-E9463883DED4)
