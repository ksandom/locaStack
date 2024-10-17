# locaStack

A basic helper script for working with a local OpenStack installation.

There is nothing new or innovative here. This was to make the tasks that I'm doing regularly, faster and reduce human error.

The original documentation that it is based off is:

* [Install OpenStack yourself on Ubuntu](https://ubuntu.com/openstack/install).
* [Tear down your OpenStack lab environment](https://ubuntu.com/tutorials/tear-down-your-openstack-lab-environment#2-stop-and-sunbeam).

## Things you might find this useful for

### Installation

```
./bin/osHelper installP1
```

Once that completes, you can run

```
./bin/osHelper installP2
```

### Uninstall

```
./bin/osHelper uninstall
```

### Reinstall

```
./bin/osHelper uninstall
```

Once that completes, you can run

```
./bin/osHelper installP2
```

### Stop/Start

I don't think this holds as much value as I originally thought. It seems to come up just fine when left alone for several (~10-15) minutes after startup. But here it is anyway:

```
./bin/osHelper stop
```

```
./bin/osHelper start
```

### See everything that it can currently do

There's more.

```
./bin/osHelper
```
