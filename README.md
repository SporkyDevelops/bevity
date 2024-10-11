# Bevity

**Version:** 0.0.0  
**Unity Version Used:** 2022.3.12f1 (4fe6e059c7ef)  

Bevity is a tool designed to allow developers to use Unity as a graphical user interface (GUI) and editor for the Bevy game engine. By using Unity’s widely-used and industry standard editor, Bevity simplifies the development process for Bevy, it enables users to  build and manage their game projects. This package/plugin allows developers to design scenes, implement game logic, and utilize custom components written in Rust, all while benefiting from Unity’s graphical editor.

___

### Overview

Currently, Bevy lacks an integrated graphical user interface (GUI), making the primary goal of this project to employ Unity as that interface. This setup enables developers to write their game logic in Bevy's Rust language with the comfort of having a live editor.

___

# Key Features

- **Custom Components**: Develop and integrate custom components in Rust that seamlessly function in Unity as MonoBehaviours.
- **Real-Time Changes**: Make modifications during play mode and see instant updates reflected in the Bevy runtime.
- **Entity and Component Parsing**: Bevity uses a custom YAML parser to convert Unity scenes into Bevy entities and components.
- **Event Handling**: Take advantage of Unity's event system to track changes in the editor and synchronize them with Bevy in real-time.
- **Built-In Primitives**: Use basic geometric shapes like cylinders, planes, cubes, spheres, and capsules for quick game level prototyping.
- **Prefab Support**: Create, manage, and load prefabs, including models formatted in GLTF.
- **Physics Integration**: Facilitates physics interactions via Bevy's Rapier crate, ensuring that collider and rigid body properties remain in sync between Unity and Bevy.

___

## Getting Started

To begin using Bevity, simply clone this repository and incorporate it into your Unity project. Make sure to include the necessary dependencies listed in the `package.json`:

```json
{
  "name": "com.wavefunk.bevity",
  "displayName": "Bevity",
  "version": "0.0.0",
  "description": "Package that lets you work in Bevy but use Unity as an editor for it",
  "dependencies": {
      "com.unity.nuget.newtonsoft-json": "3.0.2"
  }
}
```

<sub>*Last edit: Oct 11, 2024 10:00 AM EST*<sub>
