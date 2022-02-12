# Blueprint Library Tests

[![MIT License](https://img.shields.io/github/license/bUsernameIsUnavailable/BLT?style=for-the-badge)](https://github.com/bUsernameIsUnavailable/BLT/blob/master/LICENSE.md)
[![Stargazers](https://img.shields.io/github/stars/bUsernameIsUnavailable/BLT?style=for-the-badge)](https://github.com/bUsernameIsUnavailable/BLT/stargazers)
[![Network](https://img.shields.io/github/forks/bUsernameIsUnavailable/BLT?style=for-the-badge)](https://github.com/bUsernameIsUnavailable/BLT/network)
[![Issues](https://img.shields.io/github/issues/bUsernameIsUnavailable/BLT?style=for-the-badge)](https://github.com/bUsernameIsUnavailable/BLT/issues)

Developed with Unreal Engine 4.27.2

## Python Bridge Setup

> ⚠️
> **Please note that this feature depends on an editor-only plugin, meaning that it cannot be used in builds, not even development ones**
> ⚠️


The BLT plugin offers the ability to perform fuzzing on multiple types of properties, including strings. In order to generate random strings, the Python interpreter needs a certain module that can be installed by following the steps below:
<br /><br />

1. Navigate to the directory containing the Python interpreter used by the engine


2. Install the [StringGenerator](https://pypi.org/project/StringGenerator/) module using the command

```shell
python -m pip install StringGenerator
```


3. Run Unreal Engine and make sure that the Python Editor Script Plugin is enabled

![Python integration enabled](https://docs.unrealengine.com/4.27/Images/ProductionPipelines/ScriptingAndAutomation/Python/install-python-plugin.webp)
