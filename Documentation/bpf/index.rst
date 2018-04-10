=================
BPF documentation
=================

.. _man-pages: https://www.kernel.org/doc/man-pages/
.. _bpf(2): http://man7.org/linux/man-pages/man2/bpf.2.html

This is the starting point for the kernels documentation on the BPF
(Berkeley Packet Filter) facility, with a focus on the extended BPF
version.

The primary info for the bpf syscall is available in the `man-pages`_
for `bpf(2)`_.

This kernel side documentation is still work in progess.  The main
textual documentation is (for historical reasons) described in
``Documentation/networking/filter.txt``, which describe both classical and
extended BPF instruction-set.

.. class:: toc-title

	   Table of contents

.. toctree::
   :maxdepth: 2

   bpf_design_QA
   bpf_devel_QA

