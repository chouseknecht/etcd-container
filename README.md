# etcd-container 

Adds an etcd service to your [Ansible Container](https://github.com/ansible/ansible-container) project.

To add an etcd service to your project, simply run the following:

```
# Set the working directory to your project
$ cd myproject

# Install the service
$ ansible-container install chouseknecht.etcd-container
```

## Requirements

- [Ansible Container](https://github.com/ansible/ansible-container)
- An existing Ansible Container project. You can create one by running the following:
    ```
    # Create an empty project directory
    $ mkdir myproject
   
    # Set the working directory to the new directory
    $ cd myproject
  
    # Initialize the project
    $ ansible-container init 
    ```

## Role Variables

ETCD_VER
>The version of etcd to install. View the [release page](https://github.com/coreos/etcd/releases) for available versions. Defaults to "v3.0.12"

DOWNLOAD_URL
>The base URL for downloading the release .tar file. Defaults to "https://github.com/coreos/etcd/releases/download"

## Dependencies

None 


## License

Apache v2

## Author

[@chouseknecht](https://github.com/chouseknecht)
