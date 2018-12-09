**Componentes do grupo:** Eduardo Sartori Polleto e Marco Antônio Arnhold  
  
### Placa escolhida  
**Raspberry Pi 3**: escolhida devido à grande comunidade de usuários e variedade de projetos existentes na web, bem como grande compatibilidade com diversas plataformas e sistemas operacionais.  
  
### Especificação do Projeto  
O projeto irá consistir em um sistema de automação residencial, utilizando a plataforma open source Home Assistant (hass.io), permitindo o controle dos mais diversos dispositivos inteligentes, como lâmpadas, interruptores, TVs, Chromecast, entre outros. Será compatível com a Google Assistente e o IFTTT (If This Then That).  
Serão implementadas automações do tipo: "Ligar luzes quando o sol se pôr" ou "Desligar luzes quando eu sair de casa", entre outras se o tempo de projeto for suficiente. Se viável, serão utilizadas placas auxiliares com sensores (como por exemplo o NodeMCU), o qual irá se comunicar através de MQTT com o Home Assistant, possibilitando mais opções de automação.   
  
**Material utilizado:**
- Raspberry Pi 3;  
- Soquetes Sonoff;  
- Lâmpada Yeelight Color;  
- Chromecast;  
- Aplicativo 'GPS Logger' (Android);  
  
### Algumas das funções implementadas  
- Configurado um servidor DNS (DuckDNS), a fim de possibilitar o acesso via internet à interface do Home Assistant, mesmo sem um IP fixo, através do endereço 'https://smahassio.duckdns.org:8123';  
- Efetuadas integrações com os seguintes dispositivos e serviços: Yeelight Color Bulb, Soquetes Sonoff, IFTTT (usando Webhooks), Google Assistant, app GPSLogger, Google Home Mini, Chromecast, Android TV;  
- Criadas automações de acordo com nascer e pôr do sol, bem como zonas (se alguém sai da zona da casa, as luzes se desligam, por exemplo);  
- Criada integração com o Spotify, tornando o próprio Hass.io um dispositivo Spotify Connect.  
- Dentre outras.
