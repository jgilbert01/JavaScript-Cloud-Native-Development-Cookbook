# Tuning function-as-a-service

## How to do it...
1. sls create --template-url https://github.com/danteinc/js-cloud-native-cookbook/tree/master/ch9/tuning-faas --path cncb-tuning-faas
2. cd cncb-tuning-faas
3. npm install
4. npm test
5. npm run dp:lcl -- -s $MY_STAGE
6. npm run rm:lcl -- -s $MY_STAGE
