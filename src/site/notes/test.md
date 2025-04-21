---
{"dg-publish":true,"permalink":"/test/","title":"內分泌系統概覽"}
---


# 內分泌

## 神經內分泌

<div id="mind-elixir-map" style="height: 500px; border: 1px solid #ccc;"></div>

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/mind-elixir-core/dist/mind-elixir.css" />
<script src="https://cdn.jsdelivr.net/npm/mind-elixir-core/dist/mind-elixir.js"></script>

<script>
  const mind = new MindElixir({
    el: '#mind-elixir-map',
    direction: MindElixir.LEFT,
    draggable: true,
    contextMenu: true,
    toolBar: true,
    nodeMenu: true,
    keypress: true,
  });

  mind.init({
    nodeData: {
      id: 'root',
      topic: '神經內分泌',
      children: [
        {
          topic: '下視丘',
          children: [
            {
              topic: '前葉',
              children: [
                { topic: 'TRH（促甲狀腺素釋素）' },
                { topic: 'CRH（促腎上腺皮質激素釋素）' },
                { topic: 'GnRH（促性腺素釋素）' }
              ]
            },
            {
              topic: '後葉',
              children: [
                {
                  topic: 'ADH（抗利尿素）',
                  children: [
                    { topic: '過少：尿崩症' }
                  ]
                },
                { topic: '產催素' }
              ]
            }
          ]
        }
      ]
    },
    linkData: {}
  });
</script>
