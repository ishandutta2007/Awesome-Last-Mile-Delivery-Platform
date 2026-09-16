# Awesome-Last-Mile-Delivery-Platform

## Top Last-Mile Delivery Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Dispatch, Route Optimization, Driver Apps, Real-Time Tracking, Proof of Delivery & Customer Notifications*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Last-Mile Delivery**. These systems help logistics teams plan routes, dispatch drivers, track deliveries in real time, capture proof of delivery, and notify customers—covering courier, grocery, retail, and on-demand fleets.



**Examples** include Onfleet, Bringg, Routific, FarEye, Circuit, Track-POD, OptimoRoute, Upper, Shipsy, LogiNext, Tookan, DispatchTrack, Elite EXTRA, and Stuart (the category leaders).



**Open-source emphasis**: Full last-mile suites with polished driver apps and customer experiences are largely commercial. Strong open building blocks exist for **route optimization** (VROOM, OR-Tools, GraphHopper), fleet/route platforms, and courier management prototypes. This section lists the most practical open resources and is realistic about the gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Onfleet](https://onfleet.com/)**  

  Popular mid-market delivery management platform with polished dispatcher dashboard, driver app, live tracking, ETAs, and customer notifications.



- **[Bringg](https://www.bringg.com/)**  

  Enterprise delivery orchestration platform for coordinating internal fleets, 3PLs, and carriers across complex multi-channel operations.



- **[Routific](https://www.routific.com/)**  

  Route optimization and delivery planning tool focused on efficient multi-stop routes for delivery and field teams.



- **[FarEye](https://www.fareye.com/)**  

  Intelligent last-mile and delivery management platform emphasizing real-time visibility, predictive ETAs, and customer experience.



- **[Circuit](https://team.circuit.com/)**  

  Driver-first route planning and navigation app widely used by small delivery and courier teams (including Circuit for Teams / Spoke-style offerings).



- **[Track-POD](https://www.track-pod.com/)**  

  Delivery management software with route planning, tracking, proof of delivery, and customer communication features.



- **[OptimoRoute](https://optimoroute.com/)**  

  Route optimization and scheduling platform for delivery and field service, with strong multi-day and return-to-depot planning.



- **[Upper](https://www.upperinc.com/)**  

  Route planning and last-mile optimization tool aimed at delivery businesses seeking efficient daily routes.



- **[Shipsy](https://shipsy.io/)**  

  Logistics and last-mile platform used for order orchestration, tracking, and delivery operations.



- **[LogiNext](https://www.loginextsolutions.com/)**  

  Enterprise logistics platform covering last-mile, mid-mile, and related delivery orchestration capabilities.



- **[Tookan](https://tookan.app/)**  

  On-demand delivery and field workforce management platform with task assignment, tracking, and agent apps.



- **[DispatchTrack](https://www.dispatchtrack.com/)**  

  Last-mile delivery and customer experience platform focused on scheduling, tracking, and proof of delivery.



- **[Elite EXTRA](https://www.eliteextra.com/)**  

  Delivery and logistics software used by retailers and distributors for final-mile operations.



- **[Stuart](https://stuart.com/)**  

  On-demand urban delivery network and technology platform connecting businesses with couriers.



## Open-Source GitHub Projects

- **[VROOM](https://github.com/VROOM-Project/vroom)**  

  Open-source vehicle routing engine for solving capacitated VRP and related problems with time windows and other constraints.



- **[GraphHopper](https://github.com/graphhopper/graphhopper)**  

  Open-source routing engine based on OpenStreetMap data, widely used for distance/time matrices and road-network routing.



- **[Google OR-Tools](https://github.com/google/or-tools)**  

  Open optimization toolkit including powerful vehicle routing and constraint programming solvers used in many logistics projects.



- **[Fleet Route Optimizer and open fleet platforms](https://github.com/)**  

  Open-source fleet management and route optimization platforms with VRP solvers, GPS tracking concepts, and web dashboards.



- **[OptaPlanner-based delivery samples](https://github.com/)**  

  Example applications using OptaPlanner for order dispatching and route optimization (including AWS sample architectures).



- **[Courier & delivery management open projects](https://github.com/)**  

  Community platforms aiming at full courier lifecycle—order intake, routing, dispatch, tracking, proof of delivery, and settlement.



- **[Open route visualization and last-mile demos](https://github.com/)**  

  Python and web projects that optimize last-mile routes and visualize them with tools such as Kepler.gl.



- **[Driver and task assignment open prototypes](https://github.com/)**  

  Lightweight systems for managing drivers, tasks, and basic real-time status updates.



- **[Proof-of-delivery and barcode open helpers](https://github.com/)**  

  Open components for capturing signatures, photos, and scan events as part of delivery workflows.



- **[Fleetbase and open logistics cores](https://github.com/)**  

  Open logistics and fleet platforms that can be extended for last-mile dispatch and tracking use cases.



### Additional Strong Open-Source Options

- Building routing on **VROOM + GraphHopper + OR-Tools** for transparent, self-hosted optimization.

- Using open fleet/courier projects as starting points for dispatch and tracking when commercial SaaS cost or lock-in is a concern.

- Combining open solvers with commercial mapping or notification services for hybrid stacks.

- Accepting that polished driver apps, customer notification UX, large-scale multi-carrier orchestration, and turnkey support still favor commercial platforms (Onfleet, Bringg, FarEye, OptimoRoute, Track-POD, Tookan, etc.).

- Focusing open-source efforts on routing engines and core dispatch logic rather than full end-to-end last-mile suites.



**Frameworks for building custom systems**: Ingest orders → solve routes with VROOM/OR-Tools on a road graph (GraphHopper/OSM) → assign to drivers → track via mobile or GPS → capture proof of delivery → notify customers. Suitable for technical logistics teams and cost-sensitive operations. Most growing delivery businesses continue to adopt commercial last-mile platforms for speed and reliability.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Delivery platforms process location and personal data and must comply with privacy and transportation regulations. Open-source or self-built solutions require proper security, mapping licensing, and operational testing. This list is not logistics or legal advice.



---

**Made for logistics managers, courier operators, and developers building delivery systems.**

Let's keep last-mile routing efficient, transparent, and as open as practical.
