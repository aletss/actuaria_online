# How to preview this site


# 1. Install Hugo

Follow the [installation instructions](https://gohugo.io/installation/) of your OS.
Choose the `extended` edition.

# 2. Clone the repo and checkout the `hugo` branch

```bash
$ git clone git@github.com:aletss/actuaria_online.git main
$ cd actuaria_online
$ git checkout hugo
```

# 3. Start Hugo Server

Now that you're located in the repository and have checked out the `hugo` branch,
you can start a Hugo server:

```bash
$ hugo server
```

This will build your site locally and bind a port to serve it.
The port is `1313` by default.
To see the actual site go to your web browser and type `localhost:1313` in the address bar.
That's it!

Note that you don't need to stop the server in order to modify your site.
Hugo will watch for changes in the source files and rebuild your site instantly.
