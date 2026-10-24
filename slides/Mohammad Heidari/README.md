# Beyond Syscalls: Inside the World of eBPF

<p dir="ltr" align="left"><strong>Presenter:</strong> Mohammad Heidari</p>

**Session:** Talk

## Abstract (summary)

This talk introduces eBPF from a platform engineering perspective: why it emerged beyond the limitations of system calls, kernel modules, and traditional observability tools, and how it supports running programs inside the Linux kernel.

It covers the eBPF virtual machine, verifier, JIT compiler, maps, helpers, and attachment points including kprobes, tracepoints, uprobes, XDP, TC, and LSM. Production examples include Cilium for Kubernetes networking and Tetragon for runtime security. Live demonstrations trace process creation, investigate slow disk I/O, and drop packets before they reach the kernel networking stack. The session introduces bpftrace, BCC, and libbpf as starting points for writing eBPF programs.

Level: Intermediate to advanced. Basic Linux command-line knowledge is sufficient; kernel development experience is not required.

## Resources

[Presentation link](https://github.com/itsMohammadHeidari/aut-linuxfest-ebpf-presentation)

Slides have not been added to this repository yet.

[Back to all presentations](../../README.md)
