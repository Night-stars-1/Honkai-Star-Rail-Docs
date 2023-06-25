<template><div><!--
 * @Author: Night-stars-1 nujj1042633805@gmail.com
 * @Date: 2023-05-23 22:27:33
 * @LastEditors: Night-stars-1 nujj1042633805@gmail.com
 * @LastEditTime: 2023-06-20 18:50:23
 * @Description: 
 * 
 * Copyright (c) 2023 by Night-stars-1, All Rights Reserved. 
-->
<h1 id="配置" tabindex="-1"><a class="header-anchor" href="#配置" aria-hidden="true">#</a> 配置</h1>
<h2 id="配置相关" tabindex="-1"><a class="header-anchor" href="#配置相关" aria-hidden="true">#</a> 配置相关</h2>
<ul>
<li>我希望你能把必看的看完，没看完就问，不给予回答，请换个程序用，别找我</li>
</ul>
<h1 id="配置详情" tabindex="-1"><a class="header-anchor" href="#配置详情" aria-hidden="true">#</a> 配置详情</h1>
<table>
<thead>
<tr>
<th>Key</th>
<th style="text-align:center">值类型</th>
<th style="text-align:right">说明</th>
</tr>
</thead>
<tbody>
<tr>
<td>real_width</td>
<td style="text-align:center">数值</td>
<td style="text-align:right">转化后的宽度</td>
</tr>
<tr>
<td>real_height</td>
<td style="text-align:center">数值</td>
<td style="text-align:right">转化后的高度</td>
</tr>
<tr>
<td>auto_battle_persistence</td>
<td style="text-align:center">数值</td>
<td style="text-align:right">是否开启自动战斗</td>
</tr>
<tr>
<td>level</td>
<td style="text-align:center">字符串</td>
<td style="text-align:right">日志等级</td>
</tr>
<tr>
<td>github_proxy</td>
<td style="text-align:center">字符串</td>
<td style="text-align:right">github代理</td>
</tr>
<tr>
<td>rawgithub_proxy</td>
<td style="text-align:center">字符串</td>
<td style="text-align:right">rawgithub代理</td>
</tr>
<tr>
<td>webhook_url</td>
<td style="text-align:center">字符串</td>
<td style="text-align:right">未知</td>
</tr>
<tr>
<td>start</td>
<td style="text-align:center">布尔值</td>
<td style="text-align:right">是否首次启动</td>
</tr>
<tr>
<td>temp_version</td>
<td style="text-align:center">数值</td>
<td style="text-align:right">未知</td>
</tr>
<tr>
<td>star_version</td>
<td style="text-align:center">数值</td>
<td style="text-align:right">未知</td>
</tr>
<tr>
<td>open_map</td>
<td style="text-align:center">字符串</td>
<td style="text-align:right">打开地图的按键</td>
</tr>
<tr>
<td>adb</td>
<td style="text-align:center">字符串</td>
<td style="text-align:right">ADB的IP:端口</td>
</tr>
<tr>
<td>presets</td>
<td style="text-align:center">列表</td>
<td style="text-align:right">队伍预设</td>
</tr>
<tr>
<td>map_version</td>
<td style="text-align:center">数值</td>
<td style="text-align:right">未知</td>
</tr>
<tr>
<td>proxies</td>
<td style="text-align:center">字符串</td>
<td style="text-align:right">网络代理</td>
</tr>
<tr>
<td>language</td>
<td style="text-align:center">字符串</td>
<td style="text-align:right">语言</td>
</tr>
<tr>
<td>move_excursion</td>
<td style="text-align:center">数值</td>
<td style="text-align:right">移动偏移</td>
</tr>
<tr>
<td>move_division_excursion</td>
<td style="text-align:center">数值</td>
<td style="text-align:right">移动偏移倍数</td>
</tr>
<tr>
<td>sprint</td>
<td style="text-align:center">布尔值</td>
<td style="text-align:right">是否疾跑</td>
</tr>
<tr>
<td>join_time</td>
<td style="text-align:center"><a href="#%E8%BF%9B%E5%9B%BE%E6%9C%80%E5%A4%A7%E6%97%B6%E9%97%B4">查看详细</a></td>
<td style="text-align:right">进图最大时间</td>
</tr>
<tr>
<td>deficiency</td>
<td style="text-align:center">布尔值</td>
<td style="text-align:right">是否捡漏</td>
</tr>
</tbody>
</table>
<h2 id="完整配置参考" tabindex="-1"><a class="header-anchor" href="#完整配置参考" aria-hidden="true">#</a> 完整配置参考</h2>
<div class="language-json line-numbers-mode" data-ext="json"><pre v-pre class="language-json"><code><span class="token punctuation">{</span>
    <span class="token property">"real_width"</span><span class="token operator">:</span> <span class="token number">0</span><span class="token punctuation">,</span>
    <span class="token property">"auto_battle_persistence"</span><span class="token operator">:</span> <span class="token number">0</span><span class="token punctuation">,</span>
    <span class="token property">"real_height"</span><span class="token operator">:</span> <span class="token number">0</span><span class="token punctuation">,</span>
    <span class="token property">"level"</span><span class="token operator">:</span> <span class="token string">"INFO"</span><span class="token punctuation">,</span>
    <span class="token property">"github_proxy"</span><span class="token operator">:</span> <span class="token string">""</span><span class="token punctuation">,</span>
    <span class="token property">"rawgithub_proxy"</span><span class="token operator">:</span> <span class="token string">""</span><span class="token punctuation">,</span>
    <span class="token property">"webhook_url"</span><span class="token operator">:</span> <span class="token string">""</span><span class="token punctuation">,</span>
    <span class="token property">"start"</span><span class="token operator">:</span> <span class="token boolean">true</span><span class="token punctuation">,</span>
    <span class="token property">"temp_version"</span><span class="token operator">:</span> <span class="token string">"0"</span><span class="token punctuation">,</span>
    <span class="token property">"star_version"</span><span class="token operator">:</span> <span class="token string">"0"</span><span class="token punctuation">,</span>
    <span class="token property">"open_map"</span><span class="token operator">:</span> <span class="token string">"m"</span><span class="token punctuation">,</span>
    <span class="token property">"adb"</span><span class="token operator">:</span> <span class="token string">"127.0.0.1:62001"</span><span class="token punctuation">,</span>
    <span class="token property">"presets"</span><span class="token operator">:</span> <span class="token punctuation">[</span>
        <span class="token punctuation">[</span>
            <span class="token string">"丹恒"</span><span class="token punctuation">,</span>
            <span class="token string">"火主"</span><span class="token punctuation">,</span>
            <span class="token string">"姬子"</span><span class="token punctuation">,</span>
            <span class="token string">"娜塔莎"</span>
        <span class="token punctuation">]</span>
    <span class="token punctuation">]</span><span class="token punctuation">,</span>
    <span class="token property">"map_version"</span><span class="token operator">:</span> <span class="token string">"0"</span><span class="token punctuation">,</span>
    <span class="token property">"proxies"</span><span class="token operator">:</span> <span class="token string">"socks5://your_socks5_proxy"</span><span class="token punctuation">,</span>
    <span class="token property">"language"</span><span class="token operator">:</span> <span class="token string">"zh_CN"</span><span class="token punctuation">,</span>
    <span class="token property">"move_excursion"</span><span class="token operator">:</span> <span class="token number">0</span>
<span class="token punctuation">}</span>
</code></pre><div class="line-numbers" aria-hidden="true"><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div></div></div><p><strong>PS: 参考配置请不要直接复制使用，程序会自动生成，这只是给一个模板</strong></p>
<h2 id="进图最大时间" tabindex="-1"><a class="header-anchor" href="#进图最大时间" aria-hidden="true">#</a> 进图最大时间</h2>
<table>
<thead>
<tr>
<th>Key</th>
<th style="text-align:center">值类型</th>
<th style="text-align:right">说明</th>
</tr>
</thead>
<tbody>
<tr>
<td>pc</td>
<td style="text-align:center">数值</td>
<td style="text-align:right">PC进图最大时间</td>
</tr>
<tr>
<td>mnq</td>
<td style="text-align:center">数值</td>
<td style="text-align:right">模拟器进图最大时间</td>
</tr>
</tbody>
</table>
<div class="language-json line-numbers-mode" data-ext="json"><pre v-pre class="language-json"><code><span class="token punctuation">{</span>
    <span class="token property">"join_time"</span><span class="token operator">:</span> <span class="token punctuation">{</span>
        <span class="token property">"pc"</span><span class="token operator">:</span> <span class="token number">8</span><span class="token punctuation">,</span>
        <span class="token property">"mnq"</span><span class="token operator">:</span> <span class="token number">15</span>
    <span class="token punctuation">}</span>
<span class="token punctuation">}</span>
</code></pre><div class="line-numbers" aria-hidden="true"><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div><div class="line-number"></div></div></div></div></template>


