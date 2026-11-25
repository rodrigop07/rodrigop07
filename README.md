<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=170&section=header&text=Rodrigo%20Pinheiro&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Ci%C3%AAncia%20da%20Computa%C3%A7%C3%A3o%20%E2%80%A2%20Embarcados%2C%20Edge%20AI%20%26%20Sistemas&descAlignY=62&descSize=16" />
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0969da&height=170&section=header&text=Rodrigo%20Pinheiro&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Ci%C3%AAncia%20da%20Computa%C3%A7%C3%A3o%20%E2%80%A2%20Embarcados%2C%20Edge%20AI%20%26%20Sistemas&descAlignY=62&descSize=16" />
  <img width="100%" alt="Rodrigo Pinheiro" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=170&section=header&text=Rodrigo%20Pinheiro&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Ci%C3%AAncia%20da%20Computa%C3%A7%C3%A3o%20%E2%80%A2%20Embarcados%2C%20Edge%20AI%20%26%20Sistemas&descAlignY=62&descSize=16" />
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/rodrigo-pinheiro-alcantara-4112b8421/">
    <img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin-white" alt="LinkedIn" />
  </a>
  <a href="mailto:rodrigopinheiro754@outlook.com">
    <img src="https://custom-icon-badges.demolab.com/badge/Email-0078D4?style=for-the-badge&logo=mail&logoColor=white" alt="E-mail" />
  </a>
</p>

Graduando em **Ciência da Computação** na Universidade Federal do Cariri (**UFCA**).

Gosto de construir software onde as restrições são reais — seja contando ciclos em hardware e firmware com **C/C++**, rodando redes neurais offline em microcontroladores ou colocando pipelines de **Edge AI** e sistemas completos em produção com **Python** e **TypeScript**.

Atualmente aberto a **estágios** e projetos desafiadores em **Sistemas Embarcados/IoT**, **Edge AI/MLOps**, **Sistemas de Baixo Nível** ou **Engenharia de Software**.

---

## Projetos em destaque

<!-- Dica: quando tirar fotos/GIFs dos projetos, salve em ./assets/ e descomente uma linha <img src="./assets/nome.png" width="100%" /> dentro de cada card -->

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/rodrigop07/EdgeBench">EdgeBench</a></h3>
      <p><sub>IoT Industrial e Telemetria Embarcada</sub></p>
      <p>Sistema ciber-físico não invasivo para apontamento automático de produção em bancadas manuais. Detecta peças via barreira óptica por interrupção de hardware (ISR) em <strong>ESP32-S3</strong>, combina <strong>Wi-Fi/MQTT + rádio LoRa 915 MHz</strong> com bufferização offline e envia telemetria a um backend containerizado.</p>
      <p><code>C</code> · <code>ESP-IDF</code> · <code>ESP32-S3</code> · <code>LoRa 915 MHz</code> · <code>MQTT</code> · <code>Docker</code> · <code>PostgreSQL</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/rodrigop07/yolo-edge-api">yolo-edge-api</a></h3>
      <p><sub>Edge AI e MLOps em Raspberry Pi 5</sub></p>
      <p>Pipeline ponta a ponta para detecção de EPIs em tempo real com <strong>YOLOv8</strong> otimizado para borda. Inclui versionamento de datasets e modelos com <strong>DVC</strong>, API em <strong>FastAPI</strong>, streaming MJPEG com decimação de frames, <strong>CI/CD com Quality Gate</strong> e deploy contínuo com rollback via Tailscale e SSH.</p>
      <p><code>Python</code> · <code>YOLOv8</code> · <code>FastAPI</code> · <code>DVC</code> · <code>Docker</code> · <code>CI/CD</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/rodrigop07/BNO-gesture-identifier">BNO-gesture-identifier</a></h3>
      <p><sub>TinyML Offline em Microcontrolador</sub></p>
      <p>Classificador de gestos rodando 100% offline no <strong>ESP32-S3</strong> com <strong>Edge Impulse SDK</strong> (janela deslizante). Faz leitura assíncrona do IMU BNO085 via I2C a 100 Hz protegida contra <em>race conditions</em> com <strong>Mutex no FreeRTOS</strong> e interface em display OLED com <strong>LVGL</strong>.</p>
      <p><code>C</code> · <code>C++</code> · <code>ESP-IDF</code> · <code>FreeRTOS</code> · <code>TinyML</code> · <code>I2C</code> · <code>LVGL</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/rodrigop07/PongVGA">PongVGA</a></h3>
      <p><sub>Jogo Sintetizado em FPGA</sub></p>
      <p>Implementação completa de Pong em hardware descrita em <strong>Verilog</strong> (Intel Quartus). Integra controlador <strong>VGA 640×480 @ 60 Hz</strong> (divisor de clock 50→25 MHz e sincronização HSYNC/VSYNC), receptor de teclado <strong>PS/2</strong> e ROM de fontes.</p>
      <p><code>Verilog</code> · <code>FPGA</code> · <code>VGA</code> · <code>PS/2</code> · <code>Intel Quartus</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/rodrigop07/CHIP-8-Emulator">CHIP-8-Emulator</a></h3>
      <p><sub>Emulador e Depurador em C++</sub></p>
      <p>Emulador completo da arquitetura CHIP-8 escrito em <strong>C++</strong>, com depurador integrado para inspeção de registradores e memória em tempo real, interface gráfica em <strong>Dear ImGui</strong> e áudio sobre <strong>SDL2</strong>.</p>
      <p><code>C++</code> · <code>SDL2</code> · <code>Dear ImGui</code> · <code>Arquitetura</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/rodrigop07/MIPS_PIPELINE-LOGISIM">MIPS_PIPELINE-LOGISIM</a></h3>
      <p><sub>CPU MIPS 32-bit com Pipeline</sub></p>
      <p>Implementação em nível de circuito de uma CPU baseada na arquitetura <strong>MIPS de 32 bits</strong> no Logisim, contando com <strong>pipeline de 5 estágios</strong> e unidade de detecção e tratamento de hazards (<strong>Forwarding</strong> e <strong>Stall</strong>).</p>
      <p><code>Arquitetura de Computadores</code> · <code>MIPS</code> · <code>Pipeline</code> · <code>Logisim</code></p>
    </td>
  </tr>
</table>

> Outro projeto que vale a visita: [pyshell](https://github.com/rodrigop07/pyshell) — shell interativo multiplataforma escrito em Python puro para estudo de processos, sinais e I/O.

---

## No que estou trabalhando agora

- **[f1-overall](https://github.com/rodrigop07/f1-overall)** — Plataforma full-stack que avalia todos os 820 pilotos da história da Fórmula 1 (1950–2026), isolando a habilidade individual da performance do carro com regressão esparsa robusta (LMM/Ridge IRLS + Huber), *Bayesian Shrinkage* e simulador Monte Carlo de troca de assento.
- **[sistemas-distribuidos](https://github.com/rodrigop07/sistemas-distribuidos)** — Estudos práticos de concorrência e redes: servidores TCP multithread com sincronização de estado (`Lock`/`Event`), RPC e testes automatizados.
- Desenvolvimento de projetos privados em **TypeScript** e aprofundamento em sistemas embarcados e distribuídos na graduação.

---

## Com o que trabalho

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=c,cpp,py,ts,linux,docker,fastapi,postgres,raspberrypi,git,githubactions,cmake&perline=6&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=c,cpp,py,ts,linux,docker,fastapi,postgres,raspberrypi,git,githubactions,cmake&perline=6&theme=light" />
    <img src="https://skillicons.dev/icons?i=c,cpp,py,ts,linux,docker,fastapi,postgres,raspberrypi,git,githubactions,cmake&perline=6&theme=dark" alt="Principais linguagens e ferramentas" />
  </picture>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ESP--IDF-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP-IDF" />
  <img src="https://img.shields.io/badge/Verilog%20%2F%20FPGA-0071C5?style=for-the-badge&logo=intel&logoColor=white" alt="Verilog / FPGA" />
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=eclipsemosquitto&logoColor=white" alt="MQTT" />
  <img src="https://img.shields.io/badge/Edge%20Impulse-1F6FEB?style=for-the-badge&logo=edgeimpulse&logoColor=white" alt="Edge Impulse" />
  <img src="https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&logo=ultralytics&logoColor=white" alt="YOLOv8" />
  <img src="https://img.shields.io/badge/DVC-945DD6?style=for-the-badge&logo=dvc&logoColor=white" alt="DVC" />
</p>

<p align="center">
  <sub><strong>Também no dia a dia:</strong> <code>FreeRTOS</code> · <code>LoRa 915 MHz</code> · <code>I2C / UART</code> · <code>LVGL</code> · <code>MIPS Assembly</code> · <code>SDL2 / Dear ImGui</code> · <code>SciPy / Pandas</code> · <code>Sockets TCP / RPC</code> · <code>Java</code></sub>
</p>

---

## Atividade no GitHub

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=rodrigop07&theme=tokyonight" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=rodrigop07&theme=default" />
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=rodrigop07&theme=tokyonight" alt="Resumo de atividade no GitHub" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=rodrigop07&theme=tokyonight&hide_border=true&locale=pt_BR" />
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=rodrigop07&theme=default&hide_border=true&locale=pt_BR" />
    <img src="https://streak-stats.demolab.com?user=rodrigop07&theme=tokyonight&hide_border=true&locale=pt_BR" alt="Sequência de contribuições no GitHub" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rodrigop07/rodrigop07/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rodrigop07/rodrigop07/output/github-snake.svg" />
    <img alt="Gráfico animado de contribuições" src="https://raw.githubusercontent.com/rodrigop07/rodrigop07/output/github-snake-dark.svg" />
  </picture>
</p>

---

## Vamos conversar

Se quiser trocar uma ideia sobre sistemas embarcados, Edge AI, baixo nível ou conversar sobre oportunidades de estágio e projetos:

- **LinkedIn:** [linkedin.com/in/rodrigo-pinheiro-alcantara-4112b8421](https://www.linkedin.com/in/rodrigo-pinheiro-alcantara-4112b8421/)
- **E-mail:** [rodrigopinheiro754@outlook.com](mailto:rodrigopinheiro754@outlook.com)
