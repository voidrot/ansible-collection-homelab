# Changelog

## [1.1.0](https://github.com/voidrot/ansible-collection-homelab/compare/v1.0.1...v1.1.0) (2024-08-09)


### Features

* Add new roles ([#8](https://github.com/voidrot/ansible-collection-homelab/issues/8)) ([1838c67](https://github.com/voidrot/ansible-collection-homelab/commit/1838c674ce77cdf0558f8fd177a308e0b9ddd002))
* **adguard:** add new AdGuardHome role ([1838c67](https://github.com/voidrot/ansible-collection-homelab/commit/1838c674ce77cdf0558f8fd177a308e0b9ddd002))
* **dnsmasq:** add new dnsmasq role ([1838c67](https://github.com/voidrot/ansible-collection-homelab/commit/1838c674ce77cdf0558f8fd177a308e0b9ddd002))
* **keepalived:** add keepalived role ([#6](https://github.com/voidrot/ansible-collection-homelab/issues/6)) ([de776a0](https://github.com/voidrot/ansible-collection-homelab/commit/de776a005159a7ec3778e7574bc5ee9ac3e96e1c))
* **mimir:** add new mimir role ([#7](https://github.com/voidrot/ansible-collection-homelab/issues/7)) ([28f6823](https://github.com/voidrot/ansible-collection-homelab/commit/28f6823d07e2dd920c5c3d0c67e03d2c067dabf5))


### Bug Fixes

* **base:** fix lm-sensors logic ([0a02111](https://github.com/voidrot/ansible-collection-homelab/commit/0a02111f429c69676c5acbd406d877df041f126f))
* **dnsmasq:** restart service after changes to configs ([f4cfb1d](https://github.com/voidrot/ansible-collection-homelab/commit/f4cfb1da3eff07385d1767177973751825ce15c9))
* **traefik:** restart service after changes to configs ([87df221](https://github.com/voidrot/ansible-collection-homelab/commit/87df2211ea9e89f54ce877e7fe6185d3d017d19f))
* **ufw:** add missing ports from Tempo application ([8a4de44](https://github.com/voidrot/ansible-collection-homelab/commit/8a4de447bad52c5e504adab815cbbc9be8d5806f))
* undo merging ufw custom app logic ([dc201e9](https://github.com/voidrot/ansible-collection-homelab/commit/dc201e9369ba7a8715a3305c20725eacc7d7bd13))

## [1.0.1](https://github.com/voidrot/ansible-collection-homelab/compare/v1.0.0...v1.0.1) (2024-08-08)


### Bug Fixes

* **docker:** add missing apt repo template ([b63fe5a](https://github.com/voidrot/ansible-collection-homelab/commit/b63fe5a6bbb17d5deae66e542433ddce865467c0))

## 1.0.0 (2024-08-08)


### Features

* Add new roles and enhance usability ([#2](https://github.com/voidrot/ansible-collection-homelab/issues/2)) ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **base:** enhance base tasks ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **bootstrap:** rename role to base ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **docker:** add new docker role ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **ufw:** add grafana app profile ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **ufw:** add loki app profile ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **ufw:** add mimir app profile ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **ufw:** add tempo app profile ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **ufw:** add traefik app profile ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **unattended_upgrades:** add new role for enabling unattended upgrades ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))


### Bug Fixes

* **playbook:** change from include_role to import_role ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **timezone:** ensure that tzdata is installed ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
* **traefik:** change from include_tasks to import_tasks ([7add764](https://github.com/voidrot/ansible-collection-homelab/commit/7add764527c14da3139fbea0661c8e0031edc173))
