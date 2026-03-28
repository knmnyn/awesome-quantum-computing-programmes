---
layout: default
title: Data Sources
nav_order: 4
---

# 📊 Data Sources & Crawl Log

This page logs the sources consulted to build the initial directory of quantum computing programmes, along with the date they were accessed. This provides transparency on data provenance.

| Source Name | URL | Date Accessed |
|---|---|---|
| Quantum Computing Report: Universities | [Link](https://quantumcomputingreport.com/universities/) | 2026-03-25 |
| Quantum Computing Jobs: Top 10 UK Universities | [Link](https://quantumcomputingjobs.co.uk/career-advice/top-10-best-uk-universities-for-quantum-computing-quantum-technology-degrees-2025-guide) | 2026-03-25 |
| The Quantum Insider: 20 Top Universities | [Link](https://thequantuminsider.com/2024/05/21/20-top-universities-for-quantum-computing-research/) | 2026-03-25 |
| QTEdu: European Quantum Technology Education | [Link](https://qtedu.eu/programs-courses-and-trainings/higher-education) | 2026-03-25 |
| University of Surrey Physics with Quantum Computing | [Link](https://www.surrey.ac.uk/undergraduate/physics-quantum-computing) | 2026-03-25 |
| UNSW Bachelor of Engineering (Quantum Engineering) | [Link](https://www.unsw.edu.au/study/undergraduate/bachelor-of-engineering-honours-quantum) | 2026-03-25 |
| NTU BSc Applied Physics with 2nd Major in Quantum Tech | [Link](https://www.ntu.edu.sg/education/undergraduate-programme/bachelor-of-science-in-applied-physics-with-second-major-in-quantum-technologies) | 2026-03-25 |
| University of Waterloo Quantum Undergraduate Courses | [Link](https://uwaterloo.ca/institute-for-quantum-computing/graduate-studies/quantum-undergraduate-courses) | 2026-03-25 |
| Université de Sherbrooke Bachelor in Quantum Information | [Link](https://www.usherbrooke.ca/iq/en/study-at-iq-1/available-program-at-udes) | 2026-03-25 |

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
