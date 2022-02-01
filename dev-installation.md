## 1. UPDATE NODE and NPM to latest version:

### This works on Windows only
Use this [link](https://nodejs.org/en/download/)

In this case (during installation), Node is 16.13.2 and NPM is 8.1.2

## 2. Install React
```
npm i create-react-app
```

After the installation you might see **3 high severity vulnerabilities**. It can be fixed by updating to latest version of NPM. The specific version will be suggested in the console.
'''
npm install -g npm@8.4.0
'''

Or you can run
'''
npm audit fix --force
'''
