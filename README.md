# My exploration with JS in VSCode using Jupyter

## Install Deno

Deno has a Jupyter kernel. First [install Deno](https://docs.deno.com/runtime/getting_started/installation/).

```sh
curl -fsSL https://deno.land/install.sh | sh
```

Then [install the kernel](https://docs.deno.com/runtime/reference/cli/jupyter/).

```sh
deno jupyter --unstable --install
```

## VSCode support

Now install the VSCode `Jupyter` extension. You can also install the `Deno` extension if you want to have the Deno Language Server installed.

With Jupyter installed you can select `Deno` as your kernel within your notebook.

Then open the `test.ipynb` notebook in VS Code.
