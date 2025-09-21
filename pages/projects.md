---
layout: base.njk
title: Projects - NU Wireless Club
description: A showcase of projects built by NU Wireless members.
---

# Projects
From Tesla coils and RF kits to embedded gadgets and restoration work, here’s a look at what some of our members build
with the help of the Wireless makerspace.

<div class="note">
  <strong>Submit your project</strong>: Have photos, a short description, and a brief note on what you used in the
  Wireless makerspace? Send them to <code>info at nuwireless.org</code> or message an officer on Slack and we’ll add you
  to the gallery.
</div>

<style>
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
    gap: 16px;
    margin: 1rem 0 2rem;
  }

  .project-card {
    border: 1px solid #e5e5e5;
    border-radius: 12px;
    padding: 14px;
    background: #fff;
    color: #000;
    /* ensure readable text on white cards */
  }

  .project-card h3 {
    margin: 0 0 0.5rem;
    font-size: 1.1rem;
  }

  .project-card .byline {
    font-size: 0.95rem;
    opacity: 0.85;
    margin-bottom: 0.5rem;
  }

  .project-card img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    margin: 0.4rem 0 0.6rem;
    background: #eee;
  }

  .project-card .helped {
    margin: 0.5rem 0 0.2rem;
    font-weight: 600;
  }

  .project-card .links a {
    color: #007bff;
    text-decoration: underline;
  }

  .project-card .links a:hover {
    color: #0056b3;
  }

  /* disabled link style for placeholders */
  .project-card .links .disabled {
    color: #888;
    text-decoration: none;
    cursor: default;
    pointer-events: none;
  }
</style>

<!-- Garett: Transistor Radio -->
<div class="projects-grid">
  <div class="project-card">
    <h3>1953 Transistor Radio Restoration</h3>
    <div class="byline">by Garrett Compston (KW1RM)</div>
    <a href="/img/projects/garrett/transistor-radio.webp" target="_blank">
      <img src="/img/projects/garrett/transistor-radio.webp" alt="1953 Vintage transistor radio of unknown model">
    </a>
    <p>
      Restoring a 1953 transistor radio of unknown model: mapping the board layout and sourcing the antenna.
    </p>
    <div class="helped">How NU Wireless helped</div>
    <ul>
      <li>Access to soldering equipment and the circuit design skills taught in Wireless Club workshops.</li>
    </ul>
    <div class="links">
      <a href="https://drive.google.com/drive/folders/1ZMW7fkIKR5r8H-y0bjOjZCS-OrH5MKCW?usp=sharing" target="_blank"
        rel="noopener">Project Album</a>
    </div>
  </div>

  <!-- Jonah: Keyboard -->
  <div class="project-card">
    <h3>Keyboard Reverse-Engineering</h3>
    <div class="byline">by Jonah Lefkoff (K0RG)</div>
    <a href="/img/projects/jonah/keyboard-reverse-engineering/keyboard.webp" target="_blank">
      <img src="/img/projects/jonah/keyboard-reverse-engineering/keyboard.webp"
        alt="Air-traffic control keyboard and trackball">
    </a>
    <p>
      Reverse engineering a RADAR air-traffic control keyboard and trackball combo by analyzing its custom protocol,
      with the goal of building a working adapter.
    </p>
    <div class="helped">How NU Wireless helped</div>
    <ul>
      <li>Saleae logic analyzer</li>
      <li>Bench power supplies</li>
    </ul>
    <div class="links">
      <a href="https://drive.google.com/drive/folders/1Effi2AxI5PfFaezEOnMWuOSmkNJHInFM?usp=drive_link" target="_blank"
        rel="noopener">Project Album</a>
    </div>
  </div>

  <!-- Jonah: QMX+ -->
  <div class="project-card">
    <h3>QRP Labs QMX+ Kit Build</h3>
    <div class="byline">by Jonah Lefkoff (K0RG)</div>
    <a href="/img/projects/jonah/qmx-plus-transceiver/qmx-plus.webp" target="_blank">
      <img src="/img/projects/jonah/qmx-plus-transceiver/qmx-plus.webp" alt="QMX+ transceiver with toroids"
        style="width:100%; height:330px; object-fit:cover; border-radius:8px;">
    </a>
    <p>
      Built the QMX+ multiband QRP transceiver kit from QRP Labs, hand-winding 19 toroids to make a multi-band QRP rig.
      It has been used extensively as an FT8 and WSPR transceiver, with upcoming support for SSB via new firmware to be
      tested soon.
    </p>
    <div class="helped">How NU Wireless helped</div>
    <ul>
      <li>Access to lab</li>
    </ul>
    <div class="links">
      <a href="https://drive.google.com/drive/folders/1YIWrgaT-tSe2HR14HRyMiGBozre92Hmu?usp=sharing" target="_blank"
        rel="noopener">Project Album</a>
    </div>
  </div>

  <!-- Leo: Curve Tracer -->
  <div class="project-card">
    <h3>DIY Curve Tracer</h3>
    <div class="byline">by Leo Norton (KF0PQB)</div>
    <a href="/img/projects/leo/curve-tracer/curve-tracer.webp" target="_blank">
      <img src="/img/projects/leo/curve-tracer/curve-tracer.webp"
        alt="Handheld curve tracer with touchscreen display for transistor measurements, mounted on a Perfboard with other circuit components">
    </a>
    <p>
      A self-contained handheld transistor tester: plug in any transistor and the device uses dual DACs to sweep voltage
      across its terminals while applying a DC bias. The resulting current is plotted live on a small touchscreen,
      powered by an Arduino Pro Mini.
    </p>
    <p>
      Built over a couple of months, with several specialty components (like the DACs and socket)
      directly funded by the Wireless Club budget.
    </p>
    <div class="helped">How NU Wireless helped</div>
    <ul>
      <li>Funding for critical parts (DACs, transistor socket)</li>
      <li>Access to stocked components, soldering tools, and workspace</li>
      <li>Lab environment for testing and refining the design</li>
    </ul>
    <div class="links">
      <a href="https://drive.google.com/drive/folders/1K9Nz50dOoOzGvFaMNwwIFLcLi-4-jIN3?usp=sharing" target="_blank"
        rel="noopener">Project Album</a>
    </div>
  </div>

  <!-- Leo: Solid State Tesla Coil -->
  <div class="project-card">
    <h3>Solid State Tesla Coil</h3>
    <div class="byline">by Leo Norton (KF0PQB)</div>
    <a href="/img/projects/leo/solid-state-tesla-coil/solid-state-tesla-coil.webp" target="_blank">
      <img src="/img/projects/leo/solid-state-tesla-coil/solid-state-tesla-coil.webp"
        alt="Tesla coil producing long, bright arcs"
        style="width:100%; height:240px; object-fit:cover; border-radius:8px;">
    </a>
    <p>
      A high-frequency driver circuit pushes wall power through power transistors at ~300&nbsp;kHz, producing
      ~100&nbsp;kV and 1.5-ft arcs Built over a semester of winding coils, wiring, and assembly almost entirely in the
      Wireless club shack.
    </p>
    <p>
      The arcs are low-current, so they can be touched without a severe shock (though it’s not advised!).
    </p>
    <div class="helped">How NU Wireless helped</div>
    <ul>
      <li>Wire, wood panels, tools, soldering and wiring setup, and stocked components</li>
      <li>Advice from fellow members and a large knowledge base in the lab</li>
      <li>Access to test equipment for circuit debugging and measurements</li>
    </ul>
    <div class="links">
      <a href="https://drive.google.com/drive/folders/1KQmbQPp8y7mujrNOUAkkHxByyjtLaxUS?usp=sharing" target="_blank"
        rel="noopener">Project Album</a>
    </div>
  </div>

  <!-- Muhammad: 40m Woodpecker -->
  <div class="project-card">
    <h3>40-meter Woodpecker (CW transceiver)</h3>
    <div class="byline">by Muhammad Elarbi (KC1WTC)</div>
    <a href="/img/projects/muhammad/40m-woodpecker/40m-woodpecker.webp" target="_blank">
      <img src="/img/projects/muhammad/40m-woodpecker/40m-woodpecker.webp"
        alt="Partially built 40-meter Woodpecker CW transceiver kit. The green circuit board is mounted in a PCB vise, with most components soldered on, including capacitors, resistors, and ICs.">
    </a>
    <p>
      The 40m Woodpecker is a low-power CW transceiver kit for the 40-meter band.
      It uses a direct-conversion receiver with a tunable bandpass filter, audio shaping, and muting,
      paired with a simple two-stage transmitter with sidetone and QSK.
      Output is about half a watt. This build is still in progress and is being developed
      to support curriculum design for Professor Farhat’s Wireless Communication Circuits course (EECE 4574).
    </p>
    <div class="helped">How NU Wireless helped</div>
    <ul>
      <li>Comfortable lab space with 24/7 access, especially useful for late-night soldering.</li>
      <li>Soldering stations and tools.</li>
      <li>Test equipment for circuit debugging and measurements.</li>
      <li>Extra components and replacements (e.g. jumpers, capacitors) that not only filled in for a couple of missing
        parts but also let me go beyond the standard kit build, making the wiring and layout much cleaner.</li>
    </ul>
    <div class="links">
      <a href="https://drive.google.com/drive/folders/1n0t_OPANBi4KNfIC-WQKk6QxyEei0qI5?usp=sharing" target="_blank"
        rel="noopener">Project Album</a>
    </div>
  </div>

  <!-- Vlad: AIR -->
  <div class="project-card">
    <h3>AIR </h3>
    <div class="byline">by Vladyslav Aviedov (N1GNU)</div>
    <a href="/img/projects/vlad/air/air.webp" target="_blank">
      <img src="/img/projects/vlad/air/air.webp" alt="Waterfall plot showing multiple clients sharing a channel">
    </a>
    <p>
      Part of a Cornerstone project, AIR demonstrates multiple "clients" and a "controller" communicating over a
      single
      433&nbsp;MHz channel. Off-the-shelf radio modules are paired with a custom protocol written by Vlad based on
      time-division multiplexing, assigning timeslots to eliminate interference between clients.
    </p>
    <div class="helped">How NU Wireless helped</div>
    <ul>
      <li>Soldering stations and test equipment (oscilloscope, function generators)</li>
      <li>Misc. equipment (coax, cables, speakers, etc.)</li>
      <li>Consumables (protoboards, components, wires, ferrite materials)</li>
      <li>Referenced electronics books from the shack library</li>
      <li>Peer discussions and troubleshooting in the lab</li>
      <li>Borrowed radio modules specifically for AIR</li>
    </ul>
    <div class="links">
      <a href="https://drive.google.com/drive/folders/1uXnaO-ykFRLp-ZSY8e3xpjsi4eWfiroQ?usp=drive_link" target="_blank"
        rel="noopener">Project Album</a>
    </div>
  </div>

  <!-- Vlad: AM Receiver -->
  <div class="project-card">
    <h3>AM Receiver (WIP)</h3>
    <div class="byline">by Vladyslav Aviedov (N1GNU)</div>
    <a href="/img/projects/vlad/am-receiver/am-receiver.webp" target="_blank">
      <img src="/img/projects/vlad/am-receiver/am-receiver.webp"
        alt="AM receiver circuit on a custom Printed Circuit Board (PCB)">
    </a>
    <p>
      A simple diode detector AM receiver that demodulates radio into audio using a ferrite-rod antenna. It is a simple
      design that does not allow tuning, so the strongest local station dominates. PCB and tuning improvements are still
      in progress.
    </p>
    <div class="helped">How NU Wireless helped</div>
    <ul>
      <li>Soldering stations and test equipment (oscilloscope, function generators)</li>
      <li>Misc. equipment (coax, cables, speakers, etc.)</li>
      <li>Consumables (protoboards, components, wires, ferrite materials)</li>
      <li>Referenced electronics books from the shack library</li>
      <li>Peer discussions and troubleshooting in the lab</li>
    </ul>
    <div class="links">
      <a href="https://drive.google.com/drive/folders/1funfmTVaQBdwTXZYwY0IWDBM9aD1ccLW?usp=drive_link" target="_blank"
        rel="noopener">Project Album</a>
    </div>
  </div>

  <!-- Vlad: CW Transmitter -->
  <div class="project-card">
    <h3>CW Transmitter</h3>
    <div class="byline">by Vladyslav Aviedov (N1GNU)</div>
    <a href="/img/projects/vlad/cw-transmitter/cw-transmitter.webp" target="_blank">
      <img src="/img/projects/vlad/cw-transmitter/cw-transmitter.webp"
        alt="Continuous wave (CW) transmitter prototype on a Perfboard">
    </a>
    <p> Vlad's first project with radio! A Colpitts oscillator driving a random wire antenna with a carrier wave. The
      transmitter operates only while the button is pressed, allowing Morse code transmission. Despite limited frequency
      stability, a clear signal was received a few feet away using an SDR.
    </p>
    <div class="helped">How NU Wireless helped</div>
    <ul>
      <li>Soldering stations and test equipment (oscilloscope, function generators)</li>
      <li>Misc. equipment (coax, cables, speakers, etc.)</li>
      <li>Consumables (protoboards, components, wires, ferrite materials)</li>
      <li>Referenced electronics books from the shack library</li>
      <li>Peer discussions and troubleshooting in the lab</li>
    </ul>
    <div class="links">
      <a href="https://drive.google.com/drive/folders/1L2sEmNExBDAcXTlnz486V5d_wXdz8anJ?usp=sharing" target="_blank"
        rel="noopener">Project Album</a>
    </div>
  </div>