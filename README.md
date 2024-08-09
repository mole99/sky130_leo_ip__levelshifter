# sky130_leo_ip__levelshifter

This repository contains two levelshifters: One intented for 1.8V -> 3.3V and another for 3.3V -> 1.8V.

> [!IMPORTANT]  
> This is a very simple design and should only be used as a reference.

- [Documentation sky130_leo_ip__levelshifter_down](docs/sky130_leo_ip__levelshifter_down/sky130_leo_ip__levelshifter_down.md)
- [Documentation sky130_leo_ip__levelshifter_up](docs/sky130_leo_ip__levelshifter_up/sky130_leo_ip__levelshifter_up.md)

## CACE

The design is characterized with [CACE](https://github.com/efabless/cace). The documentation is auto-generated under `docs/`.
Continuous integration with CACE is also set up in this repository. Click on the "Actions" tab to see the results.

To run characterization, install CACE and execute:

For the up-levelshifter:

```
cace cace/sky130_leo_ip__levelshifter_up.yaml
```

For the down-levelshifter:

```
cace cace/sky130_leo_ip__levelshifter_down.yaml
```

In the root of this repository.

## License

The design is licensed under the Apache-2.0 license.