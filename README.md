# balena-etcher-snap
A snap for balena-etcher that targets the latest on their main branch.

## Building
To build the snap locally, ensure first that you have snap and snapcraft installed:
```sh
apt update -y
apt install snapd -y
snap install --classic snapcraft
```

Then, grab the project and build it:
```
git clone git@github.com:mattkae/balena-etcher-snap.git
cd balena-etcher-snap
snapcraft
```
