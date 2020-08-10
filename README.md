# nginx_static

Upload static content on your Nginx

## Table of content

* [Default Variables](#default-variables)
  * [dir_source](#dir_source)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### dir_source

Location of the directory that will be deployed to remote host as a static site. Can be absolute or relative.

#### Default value

```YAML
dir_source: ''
```

## Dependencies

* {'role': 'practical-ansible.nginx_project'}

## License

MIT

## Author

Pavel Žák
