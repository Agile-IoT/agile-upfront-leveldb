# agile-upfront-modules
Modules for the UpFront farmework

# Example

Do the following to test the default upfront example with this storage module:

```
git clone https://github.com/nopbyte/UPFROnt/#frozen-in-time
git clone https://github.com/Agile-IoT/agile-upfront-leveldb
cd UPFROnt
git checkout 9cdcc2b941a09f11e92f90507b1cab9d2a9d4f42
npm install --save https://github.com/Agile-IoT/agile-upfront-leveldb
mv ../agile-upfront-leveldb/example/settings.js ./example/online/settings.js
npm install
cd ./example/online/
node index.js
```
