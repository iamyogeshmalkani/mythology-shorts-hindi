# Thumbnail brief: कुंभकर्ण: एक शब्द की गलती और मिल गई छह महीने की नींद!

शीर्षक 1 के साथ जोड़ी: थंबनेल में शीर्षक के शब्द नहीं दोहराए गए। चित्र वीडियो के वही पात्र (CAST) इस्तेमाल करते हैं।

| | A (लीड) | B |
|---|---|---|
| फ़ाइल | `thumbnail-a.jpg` | `thumbnail-b.jpg` |
| शब्द | **जीभ फिसली!** | **सरस्वती ने क्या किया?** |
| दृश्य | He lies fast asleep in a huge cave with tiny lamps, six full moons floating above him | She rests as a glowing light on his lips, he stands before a blessing fire, close medium shot |
| आकार | 1280 x 720, JPEG 2 MB से कम | वही |

नियम: ≤ 4 शब्द, शीर्षक से अलग शब्द, एक मुख्य बिंदु, 168 px पर पढ़ने योग्य (जाँचा गया: नीचे की पंक्ति देखें)। पेंटिंग 768 x 512 की हैं और ऊपर-स्केल हुई हैं, इसलिए पूरे आकार में थोड़ी नरम हैं।
A को लीड रखें; अगर A आगे न निकले तो B पर जाएँ।

दोबारा बनाने का आदेश (प्रोजेक्ट फ़ोल्डर से):
`node youtube/make-thumbnail.mjs --bg assets/thumb-a.jpg --line1 "जीभ" --line2 "फिसली!" --out youtube/thumbnail-a --side bottom --size cover --pos "center top"`
