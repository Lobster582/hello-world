[Header] What is SpatialOS?

GDK for Unreal
If you're using the GDK for Unreal, this page does not apply to you. See the GDK documentation on [what SpatialOS is](https://documentation.improbable.io/gdk-for-unreal/docs/what-is-spatialos).

SpatialOS is a platform-as-a-service that runs and manages online games in the cloud.

But while it runs your game and manages the infrastructure for you, SpatialOS also enables something more than that. It runs games in a way that lets them scale further, be more complex, and have long-living persistence.

## How does it actually work?

The traditional ways to develop large online games mean that you’re either limited by the capacity of a single game server, or you have to shard your game world. 

![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

## How this architecture supports persistence, scale, and complexity

**Persistence**: The game world is stored as a scalable database of entities, providing the canonical definition of the world that server-worker instances use and make changes to.

**Scale**: Stitching server-worker instances together allows you to create a huge game world, and distribute the workload among multiple servers.

**Complexity**: You don’t just have to have one type of server-worker. You can have many types, looking after many different systems in your game world, letting you layer up functionality without overloading your servers. (You’re not limited to one system per server-worker type - each server worker type can potentially look after several systems.)

## More information

* SpatialOS [SDKs](https://documentation.improbable.io/sdks-and-data/docs)
* SpatialOS [tools](https://documentation.improbable.io/spatialos-tools/docs)

If you need further information about terminology used in this concept documentation, take a look at the [glossary](doc:glossary).

If you need information about terminology used in the Unreal Engine, take a look at the [glossary] (https://docs.unrealengine.com/en-US/Basics/Glossary/index.html).
