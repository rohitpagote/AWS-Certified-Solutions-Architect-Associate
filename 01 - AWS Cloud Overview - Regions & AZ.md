# AWS Global Infrastructure
- AWS Regions
- AWS Availability Zones
- AWS Data Centers
- AWS Edge Locations / Points of Presence

# AWS Regions
- A region is a **cluster or collection of data centers**.
- AWS has regions all around the world.
- Most AWS services are region-scoped.

## How to choose AWS Region
- **Compliance** with data governance and legal requirements: data never leaves a region without your explicit permission.
- **Proximity** to customers: reduced latency.
- **Available Services within a Region**: new services and new features are not always available in every region.
- **Pricing**: Pricing varies region to region.

# AWS Availability Zones
- Each AZ is **one or more discrete data centers with redundant power, networking and connectivity**.
- Each Region can consists of many Availability Zones (**usually 3, min 3, max 6**).
- They are separate from each other, so that they are isolated from disasters.
- They are connected with high bandwidth, ultra-low latency networking.

# AWS Points of Presence (Edge Location)
- Using POP/Edge Location, the content is delivered to end users with lower latency.
- AWS has 400+ POP (400+ Edge Locations & 10+ Regional Caches) in 90+ cities across 40+ countries.
