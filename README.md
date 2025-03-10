# Devcontainer templates repository.

> **Note:** Review devcontainers specification on templates [here](https://containers.dev/implementors/templates/)

## Template structure:

Templates can be structure in a number of ways depending on the `image` property:

```bash
src
└── template
    ├── .devcontainer
    │   └── .devcontainer.json
    ├── devcontainer-template.json
    └── README.md
```

***or**

```bash
src
└── template
    ├── .devcontainer
    │   ├── .devcontainer.json
    │   └── docker-compose.yml
    ├── devcontainer-template.json
    └── README.md
```