---
layout: default
title: Studium
permalink: /studium/
---

<style>
  .semester-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    margin-top: 2rem;
    font-family: 'Segoe UI', sans-serif;
    font-size: 1rem;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
  }

  .semester-table th,
  .semester-table td {
    padding: 1rem;
    text-align: left;
    vertical-align: top;
  }

  .semester-table thead {
    background-color: #f7f7f7;
  }

  .semester-table th {
    font-weight: 600;
    color: #444;
    border-bottom: 1px solid #ddd;
  }

  .semester-table td {
    color: #333;
  }

  .subject-code {
    color: #0000EE;
    font-weight: 600;
    white-space: nowrap;
  }

  @media (max-width: 768px) {
    .semester-table, thead, tbody, th, td, tr {
      display: block;
    }
    .semester-table thead {
      display: none;
    }
    .semester-table tr {
      margin-bottom: 1rem;
    }
    .semester-table td::before {
      content: attr(data-label);
      font-weight: bold;
      display: block;
      margin-bottom: 0.25rem;
      color: #555;
    }
  }
</style>

<table class="semester-table">
  <thead>
    <tr>
      <th>Období</th>
      <th>Předměty</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Období">Jaro 2025</td>
      <td data-label="Předměty">
        <span class="subject-code">ISKM04</span> Seminář k diplomové práci I: východiska a metodologie<br>
        <span class="subject-code">ISKM06</span> Učící se společnost<br>
        <span class="subject-code">ISKM07</span> Literatura, kultura a humanitní vědy<br>
        <span class="subject-code">ISKM09</span> LIS workshop<br>
        <span class="subject-code">ISKM10</span> Informační chování<br>
        <span class="subject-code">ISKM18</span> Praxe a stáže<br>
        <span class="subject-code">ISKM19</span> Terénní projekt<br>
        <span class="subject-code">ISKM46</span> Interakce člověk-počítač (HCI)<br>
        <span class="subject-code">ISKM54</span> Digitální design bez bariér<br>
        <span class="subject-code">CJBC805</span> Redakční práce pro nebohemisty<br>
        <span class="subject-code">CJLB706</span> Literární kompas: křižovatky teorie a praxe
      </td>
    </tr>

    <tr>
      <td data-label="Období">Podzim 2025</td>
      <td data-label="Předměty">
        <!-- připraveno k doplnění -->
        <span class="subject-code">XXXXX</span> (TBA)<br>
        <span class="subject-code">XXXXX</span> (TBA)<br>
        ...
      </td>
    </tr>
  </tbody>
</table>