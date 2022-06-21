# Quick Sauce

An SE Story & Toolkit.


## API


### Devices
Devices with availability. e.g. Which of my private devices are available? 

```shell
chmod +x ./api/devices* 
./api/devices

# sort, group, and count for even more information
./api/devices-extra
```


### Storage
Skip upload if the app already exists. _Always_ return a file id.

```shell
chmod +x ./api/storage* 
./api/storage-upload <FULLY QUALIFIED PATH TO APP>
```


_This source code is licensed under the MIT license found in the LICENSE file in the root directory of this source tree_