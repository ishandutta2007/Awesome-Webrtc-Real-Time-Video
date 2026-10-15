# Awesome-Webrtc-Real-Time-Video

#### Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Webrtc-Real-Time-Video

### Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Webrtc-Real-Time-Video

# Awesome-Webrtc-Real-Time-Video

## Top WebRTC & Real-Time Video Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on SFU Media Servers, Group Video, Real-Time Communication, Live Streaming & Programmable Video APIs*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **WebRTC & Real-Time Video**. These systems route audio and video between peers—powering meetings, live streaming, telehealth, and embedded real-time experiences.



**Examples** include Janus, LiveKit, Jitsi, Twilio Video, Agora, mediasoup, 100ms, Kurento, Daily.co, Vonage Video, and **Jitsi Videobridge** (`jitsi/jitsi-videobridge`)—a WebRTC-compatible video router.



**Open-source emphasis**: WebRTC infrastructure is exceptionally strong in open source. **Jitsi**, **LiveKit**, **mediasoup**, **Janus**, **Pion**, and **Kurento** form production-grade SFU and stack options. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Twilio Video, Agora, Vonage Video, Daily.co](https://www.twilio.com/docs/video)**  

  Programmable video APIs—SDKs, global media infrastructure, and usage-based pricing for embedding real-time video in products.



- **[100ms, LiveKit Cloud](https://www.100ms.live/)**  

  Modern real-time platforms with strong developer experience, rooms APIs, and managed SFU infrastructure.



- **[Jitsi as a Service (8x8), other hosted meeting stacks](https://jaas.8x8.vc/)**  

  Managed Jitsi-based meeting and video services for organizations that prefer not to self-host.



- **[Other commercial WebRTC / CPaaS platforms](https://www.agora.io/)**  

  Additional global media networks and turnkey conferencing products.



## Open-Source GitHub Projects



### SFU Media Servers & Full Stacks



- **[Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge)**  

  WebRTC-compatible selective forwarding unit (SFU)—the media router at the heart of Jitsi Meet.



- **[Jitsi Meet](https://github.com/jitsi/jitsi-meet)**  

  Complete open-source video conferencing stack—Web UI, signaling, and Videobridge for group meetings.



- **[LiveKit](https://github.com/livekit/livekit)**  

  End-to-end open real-time stack (SFU + SDKs)—rooms, tracks, and agents for humans and AI; strong momentum for product builders.



- **[mediasoup](https://github.com/versatica/mediasoup)**  

  Powerful open SFU library (C++/Node/Rust)—minimalist media layer, signaling-agnostic, ideal for custom large-scale group calling.



- **[Janus](https://github.com/meetecho/janus-gateway)**  

  General-purpose open WebRTC server in C—modular plugins for video rooms, streaming, recording, and gateways.



- **[Kurento](https://github.com/Kurento/kurento)**  

  Open WebRTC media server with media processing capabilities—filters, recording, and advanced pipeline graphs.



- **[OpenVidu](https://github.com/OpenVidu/openvidu)**  

  Open platform for building WebRTC applications—higher-level APIs wrapping SFU backends.



### Libraries, Tooling & Adjacent Servers



- **[Pion WebRTC](https://github.com/pion/webrtc)**  

  Pure Go WebRTC implementation—excellent for custom SFUs, embedded systems, and non-browser peers.



- **[coturn](https://github.com/coturn/coturn)**  

  Production open TURN/STUN server—essential for NAT traversal in any WebRTC deployment.



- **[MediaMTX](https://github.com/bluenviron/mediamtx)**  

  Open ready-to-use media server and proxy—WebRTC, RTSP, RTMP, HLS for cameras and broadcast-style workflows.



- **[aiortc](https://github.com/aiortc/aiortc)**  

  Open WebRTC and ORTC implementation for Python—useful for media bots and server-side participants.



- **[libdatachannel](https://github.com/paullouisageneau/libdatachannel)**  

  Open standalone WebRTC data and media library for C/C++ applications.



- **[BigBlueButton](https://github.com/bigbluebutton/bigbluebutton)**  

  Open virtual classroom platform built on WebRTC—education-focused meetings and whiteboarding.



- **[Galene / MiroTalk](https://github.com/jech/galene)**  

  Lightweight open videoconference servers for simpler self-hosted deployments.



### Additional Strong Open-Source Options



- **Meetings out of the box**: Jitsi Meet.

- **Programmable product backend**: LiveKit.

- **Custom large-scale SFU**: mediasoup.

- **Flexible C gateway**: Janus.

- **Media processing**: Kurento.

- **NAT traversal**: Always deploy coturn (or equivalent) with proper TLS and quotas.

- **Composable stacks**: SFU (LiveKit/mediasoup/Janus/JVB) + signaling app + coturn + optional recording/object storage.

- Commercial CPaaS still leads for global PoPs, compliance packages, and zero-ops media at extreme scale.



**Frameworks for building custom systems**:  

**Jitsi** for full meetings; **LiveKit** or **mediasoup** for embedded product video; **Janus** for plugin-based gateways; **Pion** for Go-native peers; **coturn** for TURN.  

SaaS APIs (Twilio, Agora, Daily, Vonage, 100ms) remove infrastructure ownership.  

Fully open WebRTC stacks are production-proven for startups through large self-hosted deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Real-time media is sensitive: encrypt in transit (mandatory in WebRTC), protect room tokens, and rate-limit TURN. Recording and storage of calls may require consent and retention policies under local law.

- Open-source SFUs offer control and cost efficiency but need capacity planning, geographic placement, and security hardening. Commercial platforms shift global media ops to the vendor. Neither replaces solid product UX and bandwidth-aware design.



---



**Made for real-time engineers, product teams, and builders of video-first experiences.**  

Let's expand open WebRTC infrastructure while recognizing the global scale and SDKs that leading commercial video platforms deliver.
