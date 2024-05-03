# Noisy-Maracas Implementation

## Tested Configuration

* `vagrant`: 2.4.1
* `ansible`: 2.16.5
* `colima`: 0.6.8
* `docker`: 26.0.0

## Development

```
colima start --cpu 2 --memory 2 --vm-type=vz --mount-type=virtiofs
vagrant up
vagrant provision
vagrant ssh
cd /vagrant
```
