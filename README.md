# Quick Sauce

An SE Story & Toolkit.


## API
<br>

### Devices
Devices with availability. e.g. Which of my private devices are available? 

```shell
# get lists of devices and availability
chmod +x ./api/devices* 
./api/devices

# sort, group, and count for even more information
./api/devices-plus
```
<br>

### Storage
Skip upload if the app already exists. _Always_ return a file id.

```shell
chmod +x ./api/storage* 
./api/storage-upload <FULLY QUALIFIED PATH TO APP>
```

<br><br>

## Helpers
<br>


### `saucejson2log`
```shell
source ./helpers/saucejson2log
saucejson2log <FULLY QUALIFIED PATH TO A JSON FORMATTED DEVICE LOG>
```
<br><br>


_This source code is licensed under the MIT license found in the LICENSE file in the root directory of this source tree_