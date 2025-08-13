<style>
  h3 {
    text-align: center;
  }
</style>


# UniForm: A Unified Multi-Task Diffusion Transformer for Audio-Video Generation

## Abstract
With the rise of diffusion models, audio-video generation has been revolutionized. However, most existing methods rely on separate modules for each modality, with limited exploration of unified generative architectures. In addition, many are confined to a single task and small-scale datasets. To address these limitations, we first propose UniForm, a unified multi-task diffusion transformer that jointly generates audio and visual modalities in a shared latent space. A single diffusion process models both audio and video, capturing the inherent correlations between sound and vision. Second, we introduce task-specific noise schemes and task tokens, enabling a single model to support multiple tasks, including text-to-audio-video, audio-to-video, and video-to-audio generation. Furthermore, by leveraging large language models and a large-scale text-audio-video combined dataset, UniForm achieves greater generative diversity than prior approaches. Extensive experiments show that UniForm achieves the state-of-the-art performance across audio-video generation tasks, producing content that is both well-aligned and close to real-world data distributions.

## Demos
We present generation results from our proposed **UniForm** across multiple audio-video synthesis conditions. Each set demonstrates three key capabilities under identical labels or captions: text-to-audio-video (T2AV), audio-to-video (A2V), and video-to-audio (V2A).


## Landscape

### splashing water
<div style="display: flex; flex-wrap: wrap; justify-content: space-around; margin-bottom: 30px;">
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">T2AV</h3>
    <video width="256" height="256" controls>
      <source src="landscape\bUntI90An-U_clip_1_17fps_t2av.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">A2V</h3>
    <video width="256" height="256" controls>
      <source src="landscape\bUntI90An-U_clip_1_17fps_ta2v.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">V2A</h3>
    <video width="256" height="256" controls>
      <source src="landscape\bUntI90An-U_clip_1_17fps_tv2a.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">V2A</h3>
    <video width="256" height="256" controls>
      <source src="landscape\bUntI90An-U_clip_1_17fps_tv2a.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

### squishing water
<div style="display: flex; flex-wrap: wrap; justify-content: space-around; margin-bottom: 30px;">
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">T2AV</h3>
    <video width="256" height="256" controls>
      <source src="landscape\KljCauisAFc_clip_1_17fps_t2av.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">A2V</h3>
    <video width="256" height="256" controls>
      <source src="landscape\KljCauisAFc_clip_1_17fps_ta2v.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">V2A</h3>
    <video width="256" height="256" controls>
      <source src="landscape\KljCauisAFc_clip_1_17fps_tv2a.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

### fire crackling
<div style="display: flex; flex-wrap: wrap; justify-content: space-around; margin-bottom: 30px;">
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">T2AV</h3>
    <video width="256" height="256" controls>
      <source src="landscape\O5zASuld4k_clip_1_17fps_t2av.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">A2V</h3>
    <video width="256" height="256" controls>
      <source src="landscape\O5zASuld4k_clip_1_17fps_ta2v.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">V2A</h3>
    <video width="256" height="256" controls>
      <source src="landscape\O5zASuld4k_clip_1_17fps_v2a.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

### underwater bubbling
<div style="display: flex; flex-wrap: wrap; justify-content: space-around; margin-bottom: 30px;">
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">T2AV</h3>
    <video width="256" height="256" controls>
      <source src="landscape\pNC1gD5jKIM_clip_2_17fps_t2av.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">A2V</h3>
    <video width="256" height="256" controls>
      <source src="landscape\pNC1gD5jKIM_clip_2_17fps_ta2v.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">V2A</h3>
    <video width="256" height="256" controls>
      <source src="landscape\pNC1gD5jKIM_clip_2_17fps_tv2a.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

### raining
<div style="display: flex; flex-wrap: wrap; justify-content: space-around; margin-bottom: 30px;">
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">T2AV</h3>
    <video width="256" height="256" controls>
      <source src="landscape\ZxGqX1cJdSQ_clip_1_17fps_t2av.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">A2V</h3>
    <video width="256" height="256" controls>
      <source src="landscape\ZxGqX1cJdSQ_clip_1_17fps_ta2v.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">V2A</h3>
    <video width="256" height="256" controls>
      <source src="landscape\ZxGqX1cJdSQ_clip_1_17fps_tv2a.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>
<!-- 
## AIST++


### lock
<div style="display: flex; flex-wrap: wrap; justify-content: space-around; margin-bottom: 30px;">
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">T2AV</h3>
    <video width="256" height="256" controls>
      <source src="aist\gLO_sBM_c01_d14_mLO0_ch04_t2av.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">A2V</h3>
    <video width="256" height="256" controls>
      <source src="aist\gLO_sBM_c01_d14_mLO0_ch04_ta2v.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">V2A</h3>
    <video width="256" height="256" controls>
      <source src="aist\gLO_sBM_c01_d14_mLO0_ch04_tv2a.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

### middle hiphop
<div style="display: flex; flex-wrap: wrap; justify-content: space-around; margin-bottom: 30px;">
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">T2AV</h3>
    <video width="256" height="256" controls>
      <source src="aist\gMH_sFM_c01_d22_mMH4_ch05_t2av.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">A2V</h3>
    <video width="256" height="256" controls>
      <source src="aist\gMH_sFM_c01_d22_mMH4_ch05_ta2v.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">V2A</h3>
    <video width="256" height="256" controls>
      <source src="aist\gMH_sFM_c01_d22_mMH4_ch05_tv2a.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

### pop
<div style="display: flex; flex-wrap: wrap; justify-content: space-around; margin-bottom: 30px;">
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">T2AV</h3>
    <video width="256" height="256" controls>
      <source src="aist\gPO_sFM_c01_d11_mPO4_ch12_t2av.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
  
  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">A2V</h3>
    <video width="256" height="256" controls>
      <source src="aist\gPO_sFM_c01_d11_mPO4_ch12_ta2v.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <div style="margin: 10px;">
    <h3 style="font-size: 18px;">V2A</h3>
    <video width="256" height="256" controls>
      <source src="aist\gPO_sFM_c01_d11_mPO4_ch12_tv2a.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>


 -->

## AudioSet


