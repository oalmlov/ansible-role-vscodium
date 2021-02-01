# vscodium

A role that installs the vscodium package and vscodium extensions (optional).

## Table of content

* [Default Variables](#default-variables)
  * [vscodium_extensions](#vscodium_extensions)
  * [vscodium_package_name](#vscodium_package_name)
  * [vscodium_repo_key](#vscodium_repo_key)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### vscodium_extensions

A list of vscodium extensions to install.

#### Default value

```YAML
vscodium_extensions: []
```

#### Example usage

```YAML
vscodium_extensions:
- ms-python.python
```

### vscodium_package_name

The vscodium package name.

#### Default value

```YAML
vscodium_package_name: codium
```

### vscodium_repo_key

The vscodium repo key.

#### Default value

```YAML
vscodium_repo_key: https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo/raw/master/pub.gpg
```

## Dependencies

None.

## License

MIT

## Author

Oskar Almlöv
