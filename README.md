# Welcome to my code world

<div align="center">
  <!-- Enhanced Online Audio Player -->
  <div style="border: 2px solid #0366d6; border-radius: 8px; padding: 15px; background: linear-gradient(135deg, #f6f8fa 0%, #e1e8ed 100%); margin: 20px 0; max-width: 500px; display: inline-block;">
    
    <div style="margin-bottom: 10px;">
      <h3 style="margin: 0; color: #24292e; font-size: 16px;">🎵 Steady Happiness - lvy010</h3>
      <p style="margin: 5px 0; color: #586069; font-size: 14px;">Coding background music</p>
    </div>

    <!-- Custom Audio Player -->
    <audio id="audioPlayer" preload="metadata" style="width: 100%; height: 40px;" controls>
      <source src="https://cdn.jsdelivr.net/gh/lvy010/lvy010@main/src/Steady%20happiness.mp3" type="audio/mpeg">
      <source src="https://raw.githubusercontent.com/lvy010/lvy010/main/src/Steady%20happiness.mp3" type="audio/mpeg">
      <source src="https://github.com/lvy010/lvy010/raw/main/src/Steady%20happiness.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>

    <!-- Player Controls -->
    <div style="margin-top: 10px; font-size: 12px;">
      <button onclick="document.getElementById('audioPlayer').play()" style="background: #28a745; color: white; border: none; padding: 5px 10px; border-radius: 4px; cursor: pointer; margin-right: 5px;">▶️ Play</button>
      <button onclick="document.getElementById('audioPlayer').pause()" style="background: #dc3545; color: white; border: none; padding: 5px 10px; border-radius: 4px; cursor: pointer; margin-right: 5px;">⏸️ Pause</button>
      <button onclick="document.getElementById('audioPlayer').currentTime=0" style="background: #6f42c1; color: white; border: none; padding: 5px 10px; border-radius: 4px; cursor: pointer;">🔄 Restart</button>
    </div>

    <div style="margin-top: 8px; font-size: 11px; color: #586069;">
      <span>🎧 Click play to enjoy while browsing my code</span>
    </div>

  </div>
</div>

<script>
// Enhanced audio player functionality
document.addEventListener('DOMContentLoaded', function() {
  const audio = document.getElementById('audioPlayer');
  if (audio) {
    // Set volume to comfortable level
    audio.volume = 0.3;
    
    // Add error handling
    audio.addEventListener('error', function() {
      console.log('Audio loading failed, trying alternative sources...');
    });
    
    // Auto-load when user hovers
    audio.addEventListener('mouseenter', function() {
      audio.load();
    });
  }
});
</script>

> "AI can help you understand open source code - this is the greatest learning opportunity in history."

> "Open source, this way of sharing with the world, is full of anticipation and goodwill. We learn and grow in open source, we respond to this expectation and live up to this goodwill. This is the luckiest thing in the world."

## Tech Stack

- **Languages**: `C++`, `Python`, `JavaScript`, `Go`, `Rust`
- **Frameworks**: `React`, `Node.js`, `Express`, `Django`, `Qt`
- **Tools**: `Git`, `Docker`, `Linux`, `MySQL`, `Redis`, `ElasticSearch`
- **Interests**: `AI/ML`, `System Design`, `Algorithm`, `Computer Vision`

## Coding Journey

### Blog & Algorithm
- [lvy's Blog](https://blog.csdn.net/2301_80171004?type=blog)
  - **787+ Original Articles** covering `AI`, `algorithms`, `system design`
  - **874K+ Total Views** with 18.5K+ likes
  - **7.9K+ Followers** and growing
  - Specialized in: `LLM`, `C++`, `Algorithm`, `Linux`, `AI Applications`

- [Algorithm Practice](https://leetcode.cn/u/hhczc/)
  - Focus areas: `Dynamic Programming`, `Graph Theory`, `Data Structures`

## Attention

- **AI & Machine Learning**: `LLM applications`, `Computer Vision`, `AIGC`
- **System Architecture**: `Distributed systems`, `Microservices`, `Database design`
- **Development Tools**: `Docker`, `CI/CD`, `Testing automation`
- **Algorithm Studies**: `Competitive programming`, `Data structures analysis`
- **Project Development**: `Game design`, `AIoT applications`, `Web3`


*"学习的使命是见识各种设计" - Keep learning, keep growing.* 
