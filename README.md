# RustKvm

RustKvm is a KVM rust refactoring project. With the development of container, cloud native and serverless technologies, virtualization technology is mainly used for container isolation, so there is a need for lightweighthypervisor such as kvm.

## Advantage

Rust language is memory safe language.
RustKvm is implemented according to the requirements of container isolation, reducing the code attack surface.

## route map

The overall architecture of kvm will not change. First, the preliminary kvm interface (vm, vcpu) is implemented, so that a specified Guest App can be run in non-root mode under intel x86. Next, the mmu part of kvm will be gradually improved; finally, the effect of running with RustVmm will be achieved.