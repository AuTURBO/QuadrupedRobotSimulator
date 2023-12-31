# Quadruped Robot Simulator

This project was automatically generated.

-   `app` - It is a folder link to the location of your _Omniverse Kit_ based app. When you clone this repository, there is no app folder.
-   `exts` - It is a folder where you can add new extensions. It was automatically added to extension search path. (Extension Manager -> Gear Icon -> Extension Search Path).

Open this folder using Visual Studio Code. It will suggest you to install few extensions that will make python experience better.

Look for "quadrupedrobot.simulator" extension in extension manager and enable it. Try applying changes to any python files, it will hot-reload and you can observe results immediately.

Alternatively, you can launch your app from console with this folder added to search path and your extension enabled, e.g.:

```
> app/isaac-sim.sh --ext-folder exts --enable quadrupedrobot.simulator
```

# App Link Setup

If `app` folder link doesn't exist or broken it can be created again. For better developer experience it is recommended to create a folder link named `app` to the _Omniverse Kit_ app installed from _Omniverse Launcher_. Convenience script to use is included.

Run:

```
> ./link_app.sh
```

If successful you should see `app` folder link in the root of this repo.

If multiple Omniverse apps is installed script will select recommended one. Or you can explicitly pass an app:

```
> ./link_app.sh --path "/home/jin/.local/share/ov/pkg/${ISAAC_FOLDER}"
```

# Acknowledge

We developed this project by referencing the code framework of the Pegasus simulator.

```
@misc{jacinto2023pegasus,
      title={Pegasus Simulator: An Isaac Sim Framework for Multiple Aerial Vehicles Simulation},
      author={Marcelo Jacinto and João Pinto and Jay Patrikar and John Keller and Rita Cunha and Sebastian Scherer and António Pascoal},
      year={2023},
      eprint={2307.05263},
      archivePrefix={arXiv},
      primaryClass={cs.RO}
}
```

# TODO

### Sharing Your Extensions

This folder is ready to be pushed to any git repository. Once pushed direct link to a git repository can be added to _Omniverse Kit_ extension search paths.

Link might look like this: `git://github.com/[user]/[your_repo].git?branch=main&dir=exts`

Notice `exts` is repo subfolder with extensions. More information can be found in "Git URL as Extension Search Paths" section of developers manual.

To add a link to your _Omniverse Kit_ based app go into: Extension Manager -> Gear Icon -> Extension Search Path
