# 🌔 moondream

<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content--moondream" class="anchor" aria-hidden="true" tabindex="-1" href="#-moondream"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🌔月梦</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个微型视觉语言模型，可以在任何地方运行</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-moondream1" class="anchor" aria-hidden="true" tabindex="-1" href="#moondream1"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">月梦1</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 SigLIP、Phi-1.5 和 LLaVA 训练数据集构建的 1.6B 参数模型。</font><font style="vertical-align: inherit;">由于使用 LLaVA 数据集，权重已获得 CC-BY-SA 许可。</font></font><a href="https://huggingface.co/spaces/vikhyatk/moondream1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在Huggingface Spaces</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上尝试一下</font><font style="vertical-align: inherit;">！</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基准测试</font></font></strong></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模型</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">VQAv2</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">核实</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维兹维兹</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文本VQA</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaVA-1.5</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">13.3B</font></font></td>
<td>80.0</td>
<td>63.3</td>
<td>53.6</td>
<td>61.3</td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaVA-1.5</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">7.3B</font></font></td>
<td>78.5</td>
<td>62.0</td>
<td>50.0</td>
<td>58.2</td>
</tr>
<tr>
<td><a href="https://huggingface.co/visheratin/MC-LLaVA-3b" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MC-LLaVA-3B</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3B</font></font></td>
<td>64.2</td>
<td>49.6</td>
<td>24.9</td>
<td>38.6</td>
</tr>
<tr>
<td><a href="https://arxiv.org/pdf/2401.02330.pdf" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LLaVA-Phi</font></font></a></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3B</font></font></td>
<td>71.4</td>
<td>-</td>
<td>35.9</td>
<td>48.6</td>
</tr>
<tr>
<td><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">月梦1</font></font></strong></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.6B</font></font></td>
<td>74.3</td>
<td>56.3</td>
<td>30.3</td>
<td>39.8</td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></strong></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图像</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/vikhyat/moondream/blob/main/assets/demo-1.jpg"><img src="/vikhyat/moondream/raw/main/assets/demo-1.jpg" alt="" style="max-width: 100%;"></a></td>
<td><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这本书的书名是什么？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">深度学习小书</font></font><br><br><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">你能告诉我关于这本书的哪些内容吗？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这本书似乎是一本名为“深度学习小书”的白色小册子。</font><font style="vertical-align: inherit;">它握在一个人的手里，看起来像是私人物品。</font><font style="vertical-align: inherit;">本书的内容侧重于深度学习的基础知识，深度学习是人工智能的一个领域，使用神经网络来处理和分析数据。</font><font style="vertical-align: inherit;">这本书很可能介绍了深度学习所涉及的概念和技术，使初学者可以轻松理解并帮助他们了解这种高级机器学习方法的基础知识。</font></font><br><br><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">那人站在哪里？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该人站在屋外的阳台或甲板上。</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/vikhyat/moondream/blob/main/assets/demo-2.jpg"><img src="/vikhyat/moondream/raw/main/assets/demo-2.jpg" alt="" style="max-width: 100%;"></a></td>
<td><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">女孩拿着什么类型的食物？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">女孩拿着一个大汉堡或汉堡，这是一种由碎肉制成的三明治，通常由牛肉饼组成，通常放在两片面包之间。</font></font><br><br><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">女人的头发是什么颜色的？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">女人的头发已经白了。</font></font><br><br><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图中的女孩在做什么？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图片中的女孩正在吃汉堡。</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/vikhyat/moondream/blob/main/assets/demo-3.jpg"><img src="/vikhyat/moondream/raw/main/assets/demo-3.jpg" alt="" style="max-width: 100%;"></a></td>
<td><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">火车是什么颜色的？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">火车是红色的。</font></font><br><br><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图中的公交车在做什么？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公共汽车沿着街道行驶，穿过十字路口，并在火车轨道上行驶。</font></font><br><br><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图中是什么类型的公共交通？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该图像展示了城市街道上的红色电车或通勤列车，这是公共交通的一种形式。</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/vikhyat/moondream/blob/main/assets/demo-4.jpg"><img src="/vikhyat/moondream/raw/main/assets/demo-4.jpg" alt="" style="max-width: 100%;"></a></td>
<td><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">女孩在看什么？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">少女一边看着镜子里的自己，一边整理着自己的制服。</font></font><br><br><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">女人的头发是什么颜色的？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">女人的头发是棕色的。</font></font><br><br><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">镜子里的女人在做什么？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">女人正在对着镜子整理头发。</font></font></td>
</tr>
<tr>
<td><a target="_blank" rel="noopener noreferrer" href="/vikhyat/moondream/blob/main/assets/demo-5.jpg"><img src="/vikhyat/moondream/raw/main/assets/demo-5.jpg" alt="" style="max-width: 100%;"></a></td>
<td><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">狗的攻击行为可能是什么原因？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这只狗的攻击性行为，露出牙齿并咆哮，可能是由多种原因造成的。</font><font style="vertical-align: inherit;">狗可能在当前环境中感到威胁、害怕或防御，例如一个房间里有一个它不熟悉的人，或者一个刺激它的情况。</font><font style="vertical-align: inherit;">或者，狗可能会对抱着它的人感受到的威胁或不适做出反应。</font><font style="vertical-align: inherit;">必须评估情况和狗的肢体语言，以确定其攻击行为的确切原因并做出相应的反应，以确保狗和相关人员的安全和福祉。</font></font><br><br><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图片中的狗是什么品种？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">照片上有一只小狗，可能是吉娃娃狗，它红着眼睛，表情卑鄙、饥饿。</font></font><br><br><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">狗是什么颜色的？</font></font></strong><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这只狗是黑白相间的。</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克隆此存储库并安装依赖项：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install -r requirements.txt</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install -r requirements.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><code>sample.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">脚本在CP&ZeroWidthSpace;&ZeroWidthSpace;U上运行模型：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python sample.py --image [IMAGE_PATH] --prompt [PROMPT]</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python sample.py --image [IMAGE_PATH] --prompt [PROMPT]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当</font></font><code>--prompt</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">未提供参数时，脚本将允许您交互式提问。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建演示</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><code>gradio_demo.py</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">脚本运行 gradio 应用程序：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">python</span> <span class="pl-s1">gradio_demo</span>.<span class="pl-s1">py</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python gradio_demo.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">局限性</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该模型可能会生成不准确的陈述。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它可能很难遵守复杂或微妙的指示。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它主要是为了理解英语而设计的。</font><font style="vertical-align: inherit;">非正式英语、俚语和非英语语言可能效果不佳。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该模型可能无法摆脱社会偏见。</font><font style="vertical-align: inherit;">用户在使用该模型时应意识到这一点并谨慎行事并进行批判性思维。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果系统提示这样做，该模型可能会生成冒犯性、不当或伤害性的内容。</font></font></li>
</ul>
</article></div>
