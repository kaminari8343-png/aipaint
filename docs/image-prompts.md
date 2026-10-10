# イラスト生成プロンプト集（うちゅうUMAずかん）

## 使い方
1. 同じチャットで、まず「共通スタイル」を最初に貼る（絵柄をそろえるため）。
2. 続けて各カードのプロンプトを1枚ずつ貼る。毎回「同じスタイルで」と添える。
3. 1枚ずつ保存し、ファイル名を **`<id>.png`**（下の見出しの id）にする。
4. `assets/cards/` に入れてもらえれば、アプリの絵文字を差し替える。

## 共通スタイル（最初に貼る）
```
I'm making illustrations for a children's educational card game for a 6-year-old Japanese boy (space and mysterious creatures). Please use this style for every image I ask for after this:
- Cute, friendly, kid-book illustration, flat vector look with soft shading
- Thick smooth outlines, bright saturated but gentle colors, rounded shapes
- ONE single subject, centered, filling about 70% of the frame
- Simple deep navy-blue background with a few tiny stars, no other clutter
- Square 1:1, 1024x1024
- Absolutely NO text, letters, numbers or logos in the image
- Nothing scary or violent: even monsters look curious and friendly
Reply "OK" and wait for my first subject.
```

## うちゅう（space）
| id | プロンプト |
|---|---|
| sun | `Same style. A smiling cute sun with soft rounded rays, warm orange and yellow glow.` |
| moon | `Same style. A glowing pale-yellow full moon with soft craters, and a cute rabbit pounding mochi on it.` |
| mercury | `Same style. Small gray-brown cratered planet Mercury with a tiny cheerful face.` |
| venus | `Same style. Golden-yellow planet Venus covered in swirling thick clouds, looks warm and a bit sweaty-cute.` |
| earth | `Same style. Planet Earth with blue oceans, green continents and white clouds, gentle smile.` |
| mars | `Same style. Rusty red planet Mars with craters and small white polar caps, cute and curious.` |
| jupiter | `Same style. Giant Jupiter with orange and cream horizontal stripes and the Great Red Spot, drawn very big and friendly.` |
| saturn | `Same style. Saturn with its big beautiful ring made of icy sparkles, pale gold colors.` |
| blackhole | `Same style. A friendly black hole: a round dark center with a glowing swirling orange-purple ring around it, soft stars being gently pulled in. Mysterious but not scary.` |
| rocket | `Same style. A red and white toy-like rocket blasting off with a cheerful orange flame and a round window.` |
| astronaut | `Same style. A cute astronaut child floating in space, giving a thumbs up, visible round helmet visor with a happy face reflection.` |
| meteor | `Same style. A bright shooting star with a long glowing tail and sparkles streaking across the night sky.` |
| galaxy | `Same style. A beautiful spiral galaxy in purple, pink and blue with a glowing yellow center and many tiny stars.` |
| iss | `Same style. The International Space Station with big golden solar panels, floating above a curved bit of blue Earth, cute simplified toy-like design.` |
| uranus | `Same style. Pale cyan-blue planet Uranus tilted on its side, rolling like a ball, with thin vertical rings.` |
| neptune | `Same style. Deep blue planet Neptune with white wispy clouds and a small dark storm spot, cool and calm.` |
| comet | `Same style. A comet: an icy rocky ball with a long glowing blue-white tail streaming behind it.` |
| constellation | `Same style. Bright stars connected by thin glowing lines forming a simple lion constellation shape, with faint outline of a cute lion behind it.` |

## UMA（uma）
| id | プロンプト |
|---|---|
| uma | `Same style. A mysterious shadowy creature silhouette in the mist with two glowing friendly eyes and a big glowing question mark shape of light (no text characters, just a shape). Curious, not scary.` |
| nessie | `Same style. Nessie, the Loch Ness monster: a cute green long-necked creature rising from a misty Scottish lake with hills behind, gentle smile.` |
| tsuchinoko | `Same style. Tsuchinoko, a Japanese legendary snake: a short, very fat snake with a thick round middle and thin tail, brown with a pale belly, sitting in grass, cute round eyes.` |
| bigfoot | `Same style. Bigfoot: a big furry brown ape-like giant standing in a pine forest, with one huge footprint in the mud next to him, shy friendly expression.` |
| yeti | `Same style. Yeti: a fluffy white-furred big creature standing on a snowy Himalayan mountain, blue face and warm smile, snowflakes around.` |
| kussie | `Same style. Kussie, a lake monster of Hokkaido, Japan: a cute blue-gray creature with a small head and round humps swimming in a calm caldera lake with green mountains.` |
| issie | `Same style. Issie, a lake monster of Lake Ikeda in Kagoshima, Japan: a cute dragon-like creature with a big smooth back and two humps rising from a sunny lake, rapeseed flowers on the shore.` |
| mokele | `Same style. Mokele-mbembe: a gentle grey-green dinosaur-like creature with a long neck and tail standing in a river in the Congo jungle, big leaves around.` |
| chupacabra | `Same style. Chupacabra drawn as a cute, friendly lizard-like creature walking on two legs with a row of small spikes on its back, in a desert at night with a big moon. Not scary.` |
| kappa | `Same style. Kappa, the Japanese river spirit: a cute green creature with a turtle shell, a small water dish on top of its head, a beak-like mouth, happily holding a cucumber, by a river.` |
| hibagon | `Same style. Hibagon: a friendly ape-like creature with dark brown fur peeking from behind trees on a green mountain in Japan, curious eyes.` |
| jackalope | `Same style. Jackalope: a cute brown rabbit with deer antlers on its head, sitting in a grassy prairie with a sunset sky.` |
| skyfish | `Same style. Skyfish: a long thin ribbon-like glowing creature with wavy side fins, flying fast across a blue sky with small clouds, looks like a flying fish made of light.` |
| kesaran | `Same style. Kesaran Pasaran: a fluffy round white puffball creature with soft fur, floating with tiny sparkles around it, small happy dot eyes.` |

## おまけ（アプリのアイコン・ホーム画面）
```
Same style. App icon: a cheerful red-and-white rocket flying up with a small cute green lake monster (Nessie) riding on it, deep navy background with stars. Rounded-square composition, 1024x1024, no text.
```
```
Same style but wide 16:9. Home screen hero artwork: a rocket flying past Saturn with Nessie, Bigfoot, Yeti and a Kappa waving from small planets. No text.
```

## うまくいかないとき
- 絵柄がぶれる → 「Same style as the previous images」と添える／最初の1枚を貼り直して「この絵柄で」と指示。
- 文字が入ってしまう → 「Remove all text and letters」と追加。
- こわい感じになった → 「Make it cuter, rounder, friendlier」と追加。
