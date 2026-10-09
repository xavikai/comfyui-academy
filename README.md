# comfyui-academy

Curs interactiu i gratuït en català per a artistes audiovisuals i 3D.

**[Obrir el curs](https://xavikai.github.io/comfyui-academy/)**

## Primera edició

15 blocs amb explicacions, experiments, pràctiques a ComfyUI, reptes i criteris d’autoavaluació. És una base formativa que cal aprofundir amb casos reals, assets i workflows validats; no es presenta com una certificació professional ni com un curs de producció complet.

8 labs de navegador: connexions tipades, seed/soroll conceptual, vores Sobel, màscara/composició, offset i repetibilitat, height/normal, cost de buffers i temps/frames. Els labs no executen models d’IA. Les operacions reals i les simulacions conceptuals estan identificades.

## Com utilitzar-lo

1. Llegeix **Entendre**.
2. Fes una predicció i prova **Experimentar**.
3. Registra una variable, una observació i una aplicació al teu projecte.
4. Fes **Portar a producció** amb ComfyUI i els models compatibles.
5. Revisa l’entrega abans de marcar el bloc.

Notes i progrés es desen al navegador. El quadern es pot exportar en JSON; els resultats dels labs de canvas, en PNG. No hi ha servidor, compte ni generació remota.

## Ruta

- 01 · Llegir un graf
- 02 · Latents, soroll i VAE
- 03 · Experiments amb KSampler
- 04 · Concept art per a 3D
- 05 · Del blockout al control
- 06 · Referències, IPAdapter i LoRA
- 07 · Màscares i inpainting
- 08 · Upscale i control de qualitat
- 09 · Famílies de models
- 10 · Textures repetibles
- 11 · PBR i mapes derivats
- 12 · Imatge a asset 3D
- 13 · Vídeo i continuïtat temporal
- 14 · So i muntatge
- 15 · Pipeline reproduïble

## Desenvolupament

Web estàtica i autocontinguda: descarrega el repositori i obre index.html en un navegador modern. No cal npm, cap build ni GPU. GitHub Pages publica main / root.

El contingut és a l’array lessons d’index.html. Els labs són a makeLab. Mantén clar què és una simulació i què és una operació real. Abans de publicar canvis, revisa navegació, controls, persistència, exportacions i errors de consola.

## Fonts i estat de validació

Les referències primàries estan enllaçades a cada bloc; consulta les variants exactes i les versions actuals. Consulta inicial: 9 octubre 2026.

Els workflows de GPU no han estat executats des d’aquesta web. La compatibilitat i els requisits s’han de confirmar en l’equip de producció. No es distribueixen pesos de models ni contingut de cursos de pagament.

Inspiració de format: [Carrot Revolt Labs](https://carrotrevoltstudio.com/labs/comfyui/).

## Desenvolupament següent

- Ampliar cada bloc amb lliçons breus i errors resolts pas a pas.
- Preparar assets originals de Blender i textures per a les pràctiques.
- Afegir workflows descarregables validats, amb versions i dades de GPU.
- Crear comparacions reals amb configuracions registrades.
- Revisar el curs amb alumnes principiants i artistes de producció.
