Credits to feffy380 who had this idea before me : https://github.com/feffy380/prompt-morph<br>
I am currently working to get the best out of his script and my script<br>

<h3><b>Features</b></h3>

<li>Interpolate between two positive prompts, it uses the AND syntaxes so it doesn't work for DDIM and PLMS.</li>
<li>Create a gif with the generated images.</li>
<li>Works for both txt2img and img2img.</li>
<li>Increase your batch count and batch size to interpolate between many seeds at the same time.</li>


<h3><b>Example</b></h3>

I interpolated between pyra and mythra from xenoblade chronicles 2.<br>
Here is the gif that the script generated.<br>
<br>
![mythra-swap-to-pyra](https://user-images.githubusercontent.com/24735555/195470874-afc3dfdc-7b35-4b23-9c34-5888a4100ac1.gif)


<h3><b>Installation</b></h3>

<li>Download the file "prompt_interpolation.py"</li>
<li>Move it to your "scripts/" folder, see https://github.com/AUTOMATIC1111/stable-diffusion-webui</li>
<li>Restart you webui.</li>


<h3><b>Usage</b></h3>

<li>Enter your first prompt in the usual prompt section, for instance</li>

```
1girl, mythra from xenoblade chronicles, best quality, upper body
```

<li>Select <i>"Script > Prompts interpolation"</i></li>

<li>Enter your second prompt in the <i>"Interpolation Prompt"</i> textbox, for instance</li>

```
1girl, pyra from xenoblade chronicles, best quality, upper body
```

<li>If you have any negative that you want all of your generated images to share, add them to the usual negative prompt textbox, for instance</li>

```
flat color, blush, lowres, bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, worst quality, low quality, normal quality, jpeg artifacts, signature, watermark, username, blurry, male focus, solo male, poorly drawn, deformed, poorly drawn face, (extra leg:1.3), (extra fingers:1.2), out of frame
```

<li>Select the number of image you want to generate between the first prompt and the second prompt. For the example I choosed 128.</li>
<li>Check <i>"Make a gif"</i></li>

<li>You can choose the number of milliseconds you want between each frame of the generated gif. I choosed 50.</li>

<li>Click the <i>"Generate"</i> button and wait... My user interface now looks like this.<li>

![image](https://user-images.githubusercontent.com/24735555/195469969-238759dc-c05f-49fc-ad1e-465a38dc5766.png)

<li>You can find the generated gif in <i>"outputs/txt2img-grids"</i>
