---
layout: default
title: Professional Certificates
nav_order: 3
---

# 📜 Professional Certificates & Online Courses

*Click on any column header to sort the table.*

| Programme Name | Provider | Mode | Focus Area | URL |
|---|---|---|---|---|
| IBM Certified Quantum Computation using Qiskit v2.X | IBM | Online | Software / Qiskit | [Link](https://www.ibm.com/training/certification/ibm-certified-quantum-computation-using-qiskit-v2x-developer-associate-C9008400) |
| Google Quantum AI Online Courses | Google / Coursera | Online | Quantum AI / Cirq | [Link](https://www.coursera.org/partners/google-quantum-ai) |
| The Hardware of a Quantum Computer | TU Delft / edX | Online | Hardware | [Link](https://www.edx.org/learn/quantum-computing/delft-university-of-technology-the-hardware-of-a-quantum-computer) |

<!-- Script to make tables sortable -->
<script src="https://cdn.jsdelivr.net/npm/tablesort@5.3.0/dist/tablesort.min.js"></script>
<script>
  document.addEventListener('DOMContentLoaded', function() {
    var tables = document.querySelectorAll('table');
    for (var i = 0; i < tables.length; i++) {
      new Tablesort(tables[i]);
    }
  });
</script>
<style>
  th[role=columnheader]:not(.no-sort) {
    cursor: pointer;
  }
  th[role=columnheader]:not(.no-sort):after {
    content: '';
    float: right;
    margin-top: 7px;
    border-width: 0 4px 4px;
    border-style: solid;
    border-color: #404040 transparent;
    visibility: hidden;
    opacity: 0;
    -ms-user-select: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    user-select: none;
  }
  th[aria-sort=ascending]:not(.no-sort):after {
    border-bottom: none;
    border-width: 4px 4px 0;
  }
  th[aria-sort]:not(.no-sort):after {
    visibility: visible;
    opacity: 0.4;
  }
  th[role=columnheader]:not(.no-sort):hover:after {
    visibility: visible;
    opacity: 1;
  }
</style>
