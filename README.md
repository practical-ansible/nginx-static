# nginx_static

Upload static content on your Nginx

## Table of content

* [Default Variables](#default-variables)
  * [dir_src](#dir_src)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### dir_src

Location of the directory that will be deployed to remote host as a static site. Can be absolute or relative.

#### Default value

```YAML
dir_src: ''
```

## Dependencies

* {'role': 'practical-ansible.nginx_project'}

## License

MIT

## Author

Pavel Žák
