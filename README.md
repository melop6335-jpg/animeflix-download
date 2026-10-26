# AnimeFlix - download

Arquivos prontos do AnimeFlix para Windows e Android. O codigo-fonte fica em um
repositorio privado.

## Baixar

| Versao | Link |
| --- | --- |
| **Windows** (PC) | **[AnimeFlix-Windows.zip](../../releases/latest/download/AnimeFlix-Windows.zip)** |
| **Android** (celular) | **[AnimeFlix.apk](../../releases/latest/download/AnimeFlix.apk)** |

## Windows - como instalar

1. Baixe o `AnimeFlix-Windows.zip`
2. Clique com o botao direito -> **Extrair tudo**
3. Abra a pasta e clique em **Instalar.bat**

Nao precisa ter Python instalado.

**Requisitos:** Windows 10/11 (Edge WebView2, que ja vem instalado) e internet.

Para desinstalar: pasta do programa -> `Desinstalar.bat`.

## Android - como instalar

O APK e uma janela do AnimeFlix que mostra a interface servida pelo seu PC.

1. Baixe o `AnimeFlix.apk` no celular
2. Abra o arquivo e permita **instalar apps desconhecidos** para o navegador/gerenciador de arquivos
3. No PC, clique em **`celular.bat`** (dentro da pasta instalada do AnimeFlix) e
   anote o endereco mostrado, parecido com `192.168.1.72:5057`
4. Se o celular nao abrir nada, rode **`liberar_firewall.bat`** como administrador (uma vez so)
5. No app, digite esse endereco e toque em **Abrir**

O celular e o PC precisam estar na **mesma rede Wi-Fi**. Wi-Fi de hotel/empresa
costuma isolar os aparelhos.

> Sem o `celular.bat` rodando no PC, o app do celular nao carrega o catalogo.
