# Get Started

This guide helps you select the right configuration for your Autoware-based low-speed autonomous (LSA) vehicle. Start by identifying your scenario, then use the reference designs to plan your build.

## Common Scenarios

| Scenario | Environment | Speed | Key Challenge | ODD Reference |
|----------|-------------|-------|---------------|---------------|
| **Campus Transport** | Outdoor, paved | <15 kph | Pedestrian interaction | [LSA-CAM-0001 to 0040](../odd-definition/outdoor/index.md) |
| **Warehouse Logistics** | Indoor, structured | <10 kph | GPS-denied navigation | [Indoor ODD](../odd-definition/indoor/index.md) |
| **Last-Mile Delivery** | Mixed terrain | <15 kph | Sidewalk/road transitions | [LSA-CAM-0020 to 0060](../odd-definition/outdoor/index.md) |

## Real World Examples

These Autoware-based projects demonstrate LSA deployments you can learn from:

### Production Deployments

| Project | Organization | Type | Links |
|---------|--------------|------|-------|
| **iseAuto** | TalTech (Estonia) | Campus shuttle | [Project](https://autolab.taltech.ee/portfolio/iseauto/) \| [Autoware Foundation](https://autoware.org/autowareio/taltech/) |
| **Aggie Auto** | NC A&T State University | Campus shuttle | [Project](https://www.aggieauto.com/about) \| [Case Study](https://autonomoustuff.com/products/case-studies/nc-a-and-t-state-university-autonomous-gem-shuttles) |

### Development Platforms

| Platform | Scale | Best For | Documentation |
|----------|-------|----------|---------------|
| **Go-Kart** | 1/3 | Algorithm development | [Details](../other-example-designs/GoKart/index.md) \| [Project](https://go-kart-upenn.readthedocs.io/) |
| **RoboRacer** | 1/10 | Education, racing | [Details](../other-example-designs/F1Tenth/index.md) \| [RoboRacer Portal](https://roboracer.ai/) |
| **AutoSDV** | Small | Home projects | [Details](../other-example-designs/AutoSDV/index.md) \| [AutoSDV Book](https://newslabntu.github.io/autosdv-book/) |

## Next Steps

1. **[Find Your Reference Design](find-your-reference-design.md)** - Use the decision flowchart to identify which configuration matches your scenario
2. **[Design Choices by Example](build-examples.md)** - Review detailed component specifications for each configuration
3. **[Hardware Configuration](../hardware-configuration/index.md)** - Deep dive into ECUs, sensors, and chassis options
4. **[Software Configuration](../software-configuration/index.md)** - Setup guides for Autoware and middleware
