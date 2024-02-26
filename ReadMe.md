### asr6601-mdk-iar

This is an unofficial ASR6601 microcontroller development kit for IAR. It includes device description and configuration files, flash algorithms and default linker script.

#### File Structure

```
config
    ├── debugger
    │   └── ASR
    │       ├── ASR6601.svd        # CMSIS-SVD
    │       └── ASR6601CB.ddf      # device description
    ├── devices
    │   └── ASR
    │       ├── ASR6601CB.i79      # device configuration
    │       └── ASR6601CB.menu
    ├── flashloader
    │   └── ASR
    │       ├── ASR6601CB.board
    │       ├── ASR6601CB.flash
    │       ├── ASR6601CB.mac      # flashloader macro
    │       └── FlashASR6601.out   # flashloader executable
    └── linker
        └── ASR
            └── asr6601cb.icf      # default linker script
```

#### How to use

Copy the `config` folder to the `arm` folder of the IAR EW ARM installation path.
