
Two‑week CKA study plan (for someone who has CKAD)
Think of it as “admin‑specific plus deep troubleshooting.” Every day:
1. 20–30 min video
2. 60–90 min hands‑on with your kubeadm cluster or kind
3. 15–20 min “docs navigation” practice on kubernetes.io

Week 1 – Cluster architecture, etcd, upgrades, storage
Day 1: Exam overview + architecture refresh 
• Goals: Understand updated 2026 CKA domains and weights; review control plane and node components in more depth.
• Focus: kube-apiserver, etcd, controller-manager, scheduler, kubelet, kube-proxy: responsibilities and key flags. Static pods vs DaemonSets for control plane components in kubeadm clusters.
• Practice: Use kubeadm init in a VM or kind cluster; inspect manifests under /etc/kubernetes/manifests. 
Practice checking component health with `kubectl get` component statuses (or replacement), `kubectl get pods -n kube-system`, and logs.

