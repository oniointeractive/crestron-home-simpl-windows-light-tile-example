# Crestron Home SIMPL Windows Light Tile Integration Example

This repository contains an example project for integrating Crestron Home with SIMPL Windows using the ONIO Crestron Home Light Tiles driver.

The example demonstrates how to connect Crestron Home Light Tile components, native Light Scenes, Quick Actions, and general room controls to a SIMPL Windows program.

It is intended for Crestron programmers, AV integrators, and smart home professionals who want to combine the flexibility of SIMPL Windows with the Crestron Home environment.

## Tutorial Video

Watch the full tutorial here:

https://youtu.be/xH_nnI3aauA?si=e9vDSfig7OacuP44

## What This Example Covers

This project demonstrates how to integrate:

- Crestron Home Light Tiles
- Crestron Home Quick Actions
- Crestron Home native Light Scenes
- General Crestron Home room controls
- Two-way communication between Crestron Home and SIMPL Windows

The goal of this example is to help you understand how Crestron Home functions can be exposed through the Integration Report and then connected inside a SIMPL Windows program.

## Included Files

This repository includes example files that can be used as a starting point for your own integration.

Depending on the repository version, the included files may contain:

- SIMPL Windows example project files
- Compiled Crestron Home integration modules
- VT Pro-e example files
- Supporting project resources

These files are provided as an example only and should be reviewed and adjusted before being used in a real installation.

## Requirements

To use this example, you will need:

- A Crestron Home processor
- A SIMPL Windows processor
- SIMPL Windows
- VT Pro-e, if you want to use or modify the included touch panel example
- Crestron Home Integration Modules
- A generated Crestron Home Integration Report
- The ONIO Crestron Home Light Tiles driver

## Crestron Home Integration Report

The most important part of this integration is the Crestron Home Integration Report.

Before connecting the SIMPL Windows program, you need to generate the Integration Report from the myCrestron Residence portal where your Crestron Home processor is registered.

The Integration Report contains the required IDs for rooms, functions, scenes, Quick Actions, and other available Crestron Home controls.

These IDs are then entered into the SIMPL Windows program so that the correct Crestron Home functions can be controlled and monitored.

Crestron documentation:

https://docs.crestron.com/en-us/8525/Content/SIMPL%20Home%20Integration%20Modules.htm

## ONIO Crestron Home Light Tiles Driver

The ONIO Crestron Home Light Tiles driver allows you to add custom Light Tile components inside Crestron Home and expose lighting-related controls that can be used in integrations such as this one.

Purchase the Crestron Home Light Tiles driver:

https://oniointeractive.lemonsqueezy.com/checkout/buy/1bf06f25-0a08-46e7-9e46-dafbfa0a658d

Watch the Light Tiles setup video:

https://www.youtube.com/watch?v=QU5TEUTCCA4

## Basic Workflow

The typical workflow is:

1. Add the ONIO Light Tiles driver to your Crestron Home project.
2. Add the required Light Tile components in Crestron Home.
3. Create any required native Light Scenes in Crestron Home.
4. Create any required Quick Actions in Crestron Home.
5. Generate the Integration Report from myCrestron Residence.
6. Open the SIMPL Windows example project.
7. Enter the required room, function, scene, and Quick Action IDs from the Integration Report.
8. Compile and upload the programs to both processors.
9. Trigger the connection from the Crestron Module.
10. Test two-way communication between Crestron Home and SIMPL Windows.

## Two-Way Communication

This integration supports two-way communication between Crestron Home and SIMPL Windows.

This means that changes made from Crestron Home can be reflected in the SIMPL Windows program, and commands triggered from SIMPL Windows can control Crestron Home functions.

The exact behavior depends on the functions, scenes, Quick Actions, and room controls included in your Crestron Home project and exposed through the Integration Report.

## Quick Actions and Light Scenes

In addition to Light Tile components, this example also demonstrates how to connect Crestron Home Quick Actions and native Light Scenes to SIMPL Windows.

This is useful when you want to trigger Crestron Home automation logic from a SIMPL Windows program, a custom touch panel interface, or another control workflow.

Quick Actions can be used for project-specific automation logic, while native Light Scenes can be used for lighting presets created directly inside Crestron Home.

## Important Security Notes

Before using this example in a real project, make sure to review all files carefully.

Do not include or publish:

- Real customer information
- Private IP addresses from customer sites
- Usernames or passwords
- API keys
- License keys
- Processor credentials
- Project-specific confidential data
- Any sensitive installation information

This repository should only contain example files that are safe to share publicly.

## Disclaimer

This example project is provided as-is, without warranty or support guarantee.

ONIO Interactive is not responsible for any issues caused by incorrect implementation, project-specific changes, unsupported configurations, or misuse of this example.

You are responsible for testing and validating the program before using it in any live installation.

## Trademarks

Crestron, Crestron Home, SIMPL Windows, VT Pro-e, and related names are trademarks or registered trademarks of Crestron Electronics, Inc.

ONIO Interactive is not affiliated with or endorsed by Crestron Electronics, Inc.

## Links

Watch the full tutorial:

https://youtu.be/xH_nnI3aauA?si=e9vDSfig7OacuP44

Purchase the Crestron Home Light Tiles driver:

https://oniointeractive.lemonsqueezy.com/checkout/buy/1bf06f25-0a08-46e7-9e46-dafbfa0a658d

Watch the Light Tiles setup video:

https://www.youtube.com/watch?v=QU5TEUTCCA4

Crestron documentation for SIMPL Home Integration Modules and Integration Report:

https://docs.crestron.com/en-us/8525/Content/SIMPL%20Home%20Integration%20Modules.htm

Support our work:

https://buymeacoffee.com/oniointeractive

ONIO Interactive YouTube channel:

http://bit.ly/38tA10M

ONIO Interactive LinkedIn:

http://bit.ly/3DV12WK

ONIO Interactive GitHub:

http://bit.ly/3LTi22a
