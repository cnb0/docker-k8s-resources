
## Docker & Kubernetes Readings
The following resources are from time-to-time refred in lectures, workshops or talks that have been performed in the past. For the sake of ease the following categories contains the references.


### Docker Analysis
- [Docker Image Layer](https://github.com/wagoodman/dive)
- [Am I contained](https://github.com/genuinetools/amicontained)

### Additional Kubernetes readings
- [RBAC](https://www.cncf.io/blog/2018/08/01/demystifying-rbac-in-kubernetes/)
- [Kubernetes RBAC 101: Authentication](https://kublr.com/blog/kubernetes-rbac-101-authentication/)
- [RAFT Algorithm](https://raft.github.io/)
- [Trouble Shooting Kubernetes](https://learnk8s.io/troubleshooting-deployments)
- [Kubernetes Certificate Rotation](https://kubernetes.io/docs/tasks/tls/certificate-rotation/)
- [Kubernetes Networking](https://sookocheff.com/post/kubernetes/understanding-kubernetes-networking-model/)
- [SecComp](https://itnext.io/seccomp-in-kubernetes-part-i-7-things-you-should-know-before-you-even-start-97502ad6b6d6)
- [Recommended Steps to Secure a DigitalOcean Kubernetes Cluster | DigitalOcean](https://www.digitalocean.com/community/tutorials/recommended-steps-to-secure-a-digitalocean-kubernetes-cluster)
- [Kubernetes Seccomp Operator](https://github.com/saschagrunert/seccomp-operator)

### Cluster Analysis
- [CIS Kubernetes Benchmark](https://www.cisecurity.org/benchmark/kubernetes/)
- [Popeye](https://github.com/derailed/popeye)
- [Kube Query](https://github.com/aquasecurity/kube-query)
- [Security Assessment techniques](https://kubesec.io/)
- [botb](https://github.com/brompwnie/botb)

### Cluster Distribution // Runtime Environments
- [k9s](https://github.com/derailed/k9s)
- [k3s](https://k3s.io/)
- [runq](https://github.com/gotoz/runq)

### Background
- [AppArmor](https://www.secjuice.com/apparmor-say-goodbye-to-remote-command-execution/)
- [GitOps](https://sysdig.com/blog/gitops-k8s-security-configwatch/)
- [Keyctl-unmask: "Going Florida" on The State Of Containerizing Linux Keyrings](https://www.antitree.com/2020/07/keyctl-unmask-going-florida-on-the-state-of-containerizing-linux-keyrings/)

### Research // Talks
- [DevSecOps](https://insinuator.net/2019/11/basta-autumn-2019/)
- [CICD Securty](https://github.com/heroku/bheu19-attacking-cloud-builds)
- [OpenShift security](https://docs.google.com/presentation/u/1/d/1o7l3BtEEQ0_P37yc5ats_DSovG6cRe7RG6OqYqbtYOY/)
- [Official kubernetes Pentest](https://www.cncf.io/blog/2019/08/06/open-sourcing-the-kubernetes-security-audit/)


## Docker Images
A collection of Docker images for testing, hacking and building purposes 

- [amass](docker-images/amass/) – [OWASP Amass](https://github.com/OWASP/Amass) in a container image on Docker Hub ([nodyd/amass](https://hub.docker.com/r/nodyd/amass))
- [ami](docker-images/ami/) – [amicontained](https://github.com/genuinetools/amicontained) in a container image on Docker Hub ([nodyd/ami](https://hub.docker.com/r/nodyd/ami))
- [ana](docker-images/ana/) – Container environment analysis tool in an image, pre-build on Docke Hub ([nodyd/ana](https://hub.docker.com/r/nodyd/ana))
- [botb](docker-images/botb/) – [Break out the Box (BOtB)](https://github.com/brompwnie/botb) in a container image, pre-build on Docke Hub ([nodyd/botb](https://hub.docker.com/r/nodyd/botb))
- [crtsh](docker-images/crtsh/) – Docker image that crawls the content from crt.sh, pre-build on Docker Hub ([nodyd/crtsh](https://hub.docker.com/r/nodyd/botb))
- [hello](docker-images/hello/) – Docker image that offers a simple webpage, pre-build on Docker Hub ([nodyd/hello](https://hub.docker.com/r/nodyd/hello))
- [httprobe](docker-images/httprobe/) – Docker image that probes webserver, pre-build on Docker Hub ([nodyd/httprobe](https://hub.docker.com/r/nodyd/httprobe))
- [kubiscan](docker-images/kubiscan) – [KubiScan](https://github.com/cyberark/KubiScan) in a container image, pre-build on Docker Hub ([nodyd/kubiscan](https://hub.docker.com/r/nodyd/kubiscan))
- [ssh](docker-images/ssh/) – Docker image that starts a SSH daemon on startup as user, prebuild on Docker Hub ([nodyd/ssh](https://hub.docker.com/r/nodyd/ssh))
- [ssl-fwd](docker-images/ssl-fwd/) – Socat in a container that wraps TLS arround another port, pre-build on Docker Hub ([nodyd/ssl-fwd](https://hub.docker.com/r/nodyd/ssl-fwd))
