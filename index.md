

## Contents

<div style="font-size: 1.15em; line-height: 1.8;">

<ol>
<li><a href="#current-capabilities">🎯 Current Capabilities</a></li>

<li><a href="#multimodal-reasoning-and-retrieval">Multimodal Reasoning and Retrieval</a>
  <ul>
    <li><a href="#documentarynet-dataset">DocumentaryNet Dataset</a></li>
    <li><a href="#downstream-task-performance-reasoning">Downstream Task Performance</a></li>
  </ul>
</li>

<li><a href="#multimodal-generation">Multimodal Generation</a>
  <ul>
    <li><a href="#metascore-dataset">MetaScore Dataset</a></li>
    <li><a href="#downstream-task-performance-generation">Downstream Task Performance</a></li>
  </ul>
</li>

<li><a href="#multimodal-stylization">Multimodal Stylization</a>
  <ul>
    <li><a href="#human-perception-aligned-effect">Human-Perception Aligned Effect</a></li>
    <li><a href="#editing-effect">Editing Effect</a></li>
    <li><a href="#downstream-task-performance-stylization">Downstream Task Performance</a></li>
  </ul>
</li>

<li><a href="#future-roadmap">🚀 Future Roadmap</a></li>
</ol>

</div>

---

## 🎯 Current Capabilities

<div style="margin: 30px 0; padding: 30px; background: linear-gradient(135deg, #dbeafe 0%, #bfdbfe 100%); border-radius: 12px; border-left: 5px solid var(--primary-color);">
  <h3 style="color: var(--text-dark); margin-top: 0; font-size: 1.5em;">Production-Ready Systems</h3>
  
  <div style="display: flex; gap: 30px; flex-wrap: wrap; margin-top: 25px;">
    <div style="flex: 1; min-width: 250px; background: white; padding: 25px; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <div style="font-size: 36px; text-align: center; margin-bottom: 15px;">🎬</div>
      <h4 style="color: var(--primary-color); text-align: center; margin: 0 0 15px 0; font-size: 1.3em;">2D Video</h4>
      <ul style="color: #475569; line-height: 2; margin: 0; padding-left: 20px;">
        <li>High-quality synthetic data generation</li>
        <li>Real-world data collection & annotation</li>
        <li>Multiple resolutions supported</li>
        <li>Temporal consistency validated</li>
      </ul>
    </div>
    
    <div style="flex: 1; min-width: 250px; background: white; padding: 25px; border-radius: 10px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
      <div style="font-size: 36px; text-align: center; margin-bottom: 15px;">🎵</div>
      <h4 style="color: var(--primary-color); text-align: center; margin: 0 0 15px 0; font-size: 1.3em;">Mono Audio</h4>
      <ul style="color: #475569; line-height: 2; margin: 0; padding-left: 20px;">
        <li>Clean audio synthesis pipeline</li>
        <li>Multi-source audio separation</li>
        <li>High-fidelity processing</li>
        <li>Audio-visual synchronization</li>
      </ul>
    </div>
  </div>
</div>

---

## Multimodal Reasoning and Retrieval

<div class="demo-instructions">
  <p><strong>Focus:</strong> Enable intelligent reasoning and retrieval across text, audio, and video modalities with semantic understanding.</p>
</div>

### DocumentaryNet Dataset

**DocumentaryNet** is the first large-scale multimodal dataset with separate audio tracks (sound effects, music, speech) designed for advanced reasoning and retrieval tasks.

**Key Features:**
- 📊 **Scale:** X hours of annotated documentary footage
- 🎯 **Granularity:** Frame-level and clip-level annotations
- 🎼 **Audio Tracks:** Separated sound effects, music, speech, and ambient audio
- 🔍 **Use Cases:** Multi-modal search, video understanding, audio-visual correspondence

**Current Status:** ✅ Production-ready with 2D video and mono audio

### Downstream Task Performance

<table style="width: 100%; border-collapse: collapse; margin: 20px 0;">
  <tr style="background: linear-gradient(135deg, var(--primary-color), var(--secondary-color)); color: white;">
    <th style="padding: 15px; text-align: left; font-size: 1.1em;">Task</th>
    <th style="padding: 15px; text-align: center; font-size: 1.1em;">Metric</th>
    <th style="padding: 15px; text-align: center; font-size: 1.1em;">Performance</th>
  </tr>
  <tr style="background: #f8fafc;">
    <td style="padding: 15px; border-bottom: 1px solid #e2e8f0;">Video-Text Retrieval</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0;">Recall@10</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0; font-weight: 600;">-</td>
  </tr>
  <tr>
    <td style="padding: 15px; border-bottom: 1px solid #e2e8f0;">Audio-Visual Matching</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0;">Accuracy</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0; font-weight: 600;">-</td>
  </tr>
  <tr style="background: #f8fafc;">
    <td style="padding: 15px;">Cross-Modal Reasoning</td>
    <td style="padding: 15px; text-align: center;">F1 Score</td>
    <td style="padding: 15px; text-align: center; font-weight: 600;">-</td>
  </tr>
</table>

---

## Multimodal Generation

<div class="demo-instructions">
  <p><strong>Focus:</strong> Generate high-quality multimodal content from text descriptions, with emphasis on symbolic music generation.</p>
</div>

### MetaScore Dataset

**MetaScore** is the largest symbolic music dataset with rich metadata and natural language descriptions, enabling text-to-music generation at scale.

**Key Features:**
- 🎼 **Scale:** X symbolic music pieces with captions
- 📝 **Annotations:** Natural language descriptions, emotion tags, style metadata
- 🎹 **Diversity:** Multiple genres, instruments, and compositional styles
- 🔧 **Format:** MIDI, MusicXML, ABC notation

**Current Status:** ✅ Production-ready dataset and generation models

### Downstream Task Performance

<table style="width: 100%; border-collapse: collapse; margin: 20px 0;">
  <tr style="background: linear-gradient(135deg, var(--primary-color), var(--secondary-color)); color: white;">
    <th style="padding: 15px; text-align: left; font-size: 1.1em;">Task</th>
    <th style="padding: 15px; text-align: center; font-size: 1.1em;">Metric</th>
    <th style="padding: 15px; text-align: center; font-size: 1.1em;">Performance</th>
  </tr>
  <tr style="background: #f8fafc;">
    <td style="padding: 15px; border-bottom: 1px solid #e2e8f0;">Text-to-Music Generation</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0;">FID</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0; font-weight: 600;">-</td>
  </tr>
  <tr>
    <td style="padding: 15px; border-bottom: 1px solid #e2e8f0;">Style Transfer</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0;">Accuracy</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0; font-weight: 600;">-</td>
  </tr>
  <tr style="background: #f8fafc;">
    <td style="padding: 15px;">Human Preference</td>
    <td style="padding: 15px; text-align: center;">Win Rate</td>
    <td style="padding: 15px; text-align: center; font-weight: 600;">-</td>
  </tr>
</table>

---

## Multimodal Stylization

<div class="demo-instructions">
  <p><strong>Focus:</strong> Apply human-perception-aligned effects and perform joint audio-visual editing for creative content stylization.</p>
</div>

**Current Implementation:** 2D Video + Mono Audio

We present two complementary datasets:
- **ObjectEmphasis:** Human-perception-aligned audio-visual effects
- **SAVEBench:** Synthetic and real-world joint editing benchmarks

### Human-Perception Aligned Effect

**ObjectEmphasis** enables perceptually-guided stylization that maintains natural audio-visual correspondence.

**Capabilities:**
- 🎨 Emphasis/de-emphasis of specific objects
- 🔊 Audio effect intensity control
- 👁️ Eye-tracking guided editing
- ⚡ Real-time preview

### Editing Effect

**Joint Audio-Visual Editing** across three data configurations:

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin: 25px 0;">
  <div style="padding: 20px; background: #f0f9ff; border-radius: 8px; border-left: 4px solid var(--primary-color);">
    <h4 style="color: var(--text-dark); margin-top: 0;">🔬 Synthetic + Synthetic</h4>
    <p style="color: #475569; margin: 0;">Synthetic audio paired with synthetic video for controlled experiments</p>
  </div>
  
  <div style="padding: 20px; background: #f0f9ff; border-radius: 8px; border-left: 4px solid var(--primary-color);">
    <h4 style="color: var(--text-dark); margin-top: 0;">🔀 Synthetic + Real</h4>
    <p style="color: #475569; margin: 0;">Synthetic audio with real video for domain adaptation</p>
  </div>
  
  <div style="padding: 20px; background: #f0f9ff; border-radius: 8px; border-left: 4px solid var(--primary-color);">
    <h4 style="color: var(--text-dark); margin-top: 0;">🌍 Real + Real</h4>
    <p style="color: #475569; margin: 0;">Real audio and video for production-quality results</p>
  </div>
</div>

### Downstream Task Performance

<table style="width: 100%; border-collapse: collapse; margin: 20px 0;">
  <tr style="background: linear-gradient(135deg, var(--primary-color), var(--secondary-color)); color: white;">
    <th style="padding: 15px; text-align: left; font-size: 1.1em;">Task</th>
    <th style="padding: 15px; text-align: center; font-size: 1.1em;">Metric</th>
    <th style="padding: 15px; text-align: center; font-size: 1.1em;">Performance</th>
  </tr>
  <tr style="background: #f8fafc;">
    <td style="padding: 15px; border-bottom: 1px solid #e2e8f0;">Object Removal</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0;">PSNR / SSIM</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0; font-weight: 600;">-</td>
  </tr>
  <tr>
    <td style="padding: 15px; border-bottom: 1px solid #e2e8f0;">Audio-Visual Sync</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0;">Sync Score</td>
    <td style="padding: 15px; text-align: center; border-bottom: 1px solid #e2e8f0; font-weight: 600;">-</td>
  </tr>
  <tr style="background: #f8fafc;">
    <td style="padding: 15px;">Human Evaluation</td>
    <td style="padding: 15px; text-align: center;">MOS</td>
    <td style="padding: 15px; text-align: center; font-weight: 600;">-</td>
  </tr>
</table>

---

## 🚀 Future Roadmap

<div style="margin: 30px 0; padding: 35px; background: linear-gradient(135deg, #fef3c7 0%, #fde68a 100%); border-radius: 12px; border-left: 5px solid #f59e0b;">
  <h3 style="color: #78350f; margin-top: 0; font-size: 1.5em;">Upcoming Capabilities</h3>
  
  <div style="margin-top: 25px;">
    <div style="margin-bottom: 30px; padding: 20px; background: white; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
      <h4 style="color: var(--primary-color); margin: 0 0 15px 0; font-size: 1.3em;">📅 Phase 1: Enhanced Audio (Q2 2025)</h4>
      <ul style="color: #475569; line-height: 2; margin: 0; padding-left: 25px;">
        <li><strong>Binaural Audio:</strong> 3D spatial audio with head-related transfer functions</li>
        <li><strong>Spatial Audio:</strong> Multi-channel surround sound and ambisonic formats</li>
        <li><strong>Applications:</strong> Immersive VR/AR experiences, cinematic audio</li>
      </ul>
    </div>
    
    <div style="padding: 20px; background: white; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
      <h4 style="color: var(--primary-color); margin: 0 0 15px 0; font-size: 1.3em;">📅 Phase 2: 3D Video (Q3 2025)</h4>
      <ul style="color: #475569; line-height: 2; margin: 0; padding-left: 25px;">
        <li><strong>Stereoscopic 3D:</strong> Depth perception for enhanced viewing</li>
        <li><strong>Volumetric Video:</strong> 6DOF content for VR/AR</li>
        <li><strong>Point Cloud Data:</strong> Dynamic 3D scene reconstruction</li>
        <li><strong>Applications:</strong> Virtual production, 3D content creation</li>
      </ul>
    </div>
  </div>
  
  <div style="margin-top: 30px; padding: 20px; background: rgba(255, 255, 255, 0.7); border-radius: 8px; border: 2px dashed #f59e0b;">
    <p style="margin: 0; color: #78350f; font-size: 1.1em; text-align: center;">
      <strong>📢 Stay tuned:</strong> Gradual rollout with backward compatibility for all existing 2D + mono audio pipelines
    </p>
  </div>
</div>
