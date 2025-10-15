# UrbanVerse: Scaling Urban Simulation by Watching City-Tour Videos

[[Project Page]](https://urbanverseproject.github.io/) [[arXiv]](https://arxiv.org/pdf/2505.03729)  

**arXiv preprint, 2025.**
    
<div style="background-color: #333; padding: 16px 20px; border-radius: 8px; color: #eee; font-family: sans-serif; line-height: 1.6;">
  <h1 class="subtitle is-1 publication-title is-size-4-mobile" style="font-size: 1.2rem; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8); margin-bottom: 0.5rem; text-align: left;">
        <a href="https://oatmealliu.github.io/" target="_blank" style="color: white; text-decoration: none; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8); font-family: 'Roboto Mono', monospace !important;" onmouseover="this.style.textDecoration='underline';" onmouseout="this.style.textDecoration='none';">Mingxuan Liu</a><sup>1,2,*</sup> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <a href="https://dhlinv.github.io/" target="_blank" style="color: white; text-decoration: none; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8); font-family: 'Roboto Mono', monospace !important;" onmouseover="this.style.textDecoration='underline';" onmouseout="this.style.textDecoration='none';">Honglin He</a><sup>1,*</sup> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <a href="https://scholar.google.com/citations?user=xf1T870AAAAJ&hl=en" target="_blank" style="color: white; text-decoration: none; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8); font-family: 'Roboto Mono', monospace !important;" onmouseover="this.style.textDecoration='underline';" onmouseout="this.style.textDecoration='none';">Elisa Ricci</a><sup>2,3</sup> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <a href="https://wywu.github.io/" target="_blank" style="color: white; text-decoration: none; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8); font-family: 'Roboto Mono', monospace !important;" onmouseover="this.style.textDecoration='underline';" onmouseout="this.style.textDecoration='none';">Wayne Wu</a><sup>1</sup> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <a href="https://boleizhou.github.io/" target="_blank" style="color: white; text-decoration: none; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8); font-family: 'Roboto Mono', monospace !important;" onmouseover="this.style.textDecoration='underline';" onmouseout="this.style.textDecoration='none';">Bolei Zhou</a><sup>1</sup>
      </h1>
       <!-- Institutions -->
       <h1 class="subtitle is-1 publication-title is-size-4-mobile" style="font-size: 1.2rem; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8); margin-bottom: 0.8rem; text-align: left;">
         <sup>1</sup>University of California, Los Angeles &nbsp;&nbsp;&nbsp; <sup>2</sup>University of Trento &nbsp;&nbsp;&nbsp; <sup>3</sup>Fondazione Bruno Kessler
       </h1>
</div>

## Updates

- **Sep 15, 2025:** Simulation code and preliminary sim2real code released.
- **Jul 6, 2025:** Initial real-to-sim pipeline release. 

## TODO

- [x] Release real‑to‑sim pipeline (July 15th, 2025)
- [x] Release the video dataset (July 15th, 2025) 
- [x] Release simulation pipeline (September 15th, 2025) 
- [x] Release sim2real code (September 15th, 2025) 

# VideoMimic Real-to-Sim

VideoMimic’s [real-to-sim pipeline](real2sim/README.md) reconstructs 3D environments and human motion from single-camera videos and retargets the motion to humanoid robots for imitation learning. It extracts human poses in world coordinates, maps them to robot configurations, and reconstructs environments as pointclouds later converted to meshes.

 
