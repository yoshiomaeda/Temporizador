# Temporizador HTML

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logote
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=forge&logo=css3&logoColor=white
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=oColor=black
![Responsive](https://img.shields.io/badge/Responsive-Mobile%20Friendly-success?style=for-the-b](https://img.shields.io/badge/Offline?style=for-the-badge
![LocalStorage](https://img.shields.io/badge/Storage-LocalStorage-orange?dge
Temporizador desenvolvido em HTML, CSS e JavaScript puro, focado em produtividade, gestão de tempo e uso rápido tanto em desktop quanto em dispositivos móveis. Próprio para quem fica/trabalha com o navegador aberto permanentemente.

![Temporizador](https://github.com/yoshiomaeda/Temporizador/blob/main/temporizadorV09.png)

---

## Recursos

### Controle de Tempo

- Contagem regressiva em tempo real.
- Botões de duração pré-definida.
- Duração personalizada.
- Início automático ao selecionar um tempo.
- Pausa e retomada.
- Parada e reinicialização.

### Ajuste Dinâmico

Durante a execução é possível ajustar o tempo sem interromper a contagem:

- `-5m`
- `-1m`
- `+1m`
- `+5m`

### Indicadores Visuais

- Tempo restante.
- Tempo decorrido.
- Barra de progresso.
- Percentual restante.
- Mudança automática de cores conforme o tempo se aproxima do fim.

### Previsão de Término

Exibe automaticamente o horário previsto para conclusão da atividade.

### Alertas

- Alarme sonoro.
- Notificação do navegador.
- Destaque visual na aba ao término da contagem.

### Nome da Atividade

Permite identificar cada temporizador com um nome personalizado.

Exemplos:

- Estudo
- Reunião
- Atendimento
- Treinamento
- Pausa

### Histórico

O sistema registra automaticamente:

- Nome da atividade
- Horário de início
- Horário de término
- Duração utilizada

### Tempos Recentes

Os últimos tempos utilizados aparecem automaticamente como atalhos.

Exemplo:

```text
15 min | 3 min | 30 min | 1 min
```

Ao clicar em um deles:

- A duração é selecionada.
- A contagem é iniciada imediatamente.

### Persistência Local

As configurações são armazenadas no navegador:

- Nome da atividade
- Última duração utilizada
- Valor personalizado
- Histórico de execuções

### Interface Responsiva

Compatível com:

- Desktop
- Tablet
- Smartphone

---

## Personalização

Os tempos exibidos nos botões podem ser alterados facilmente:

```javascript
const OPCOES_TEMPO_MINUTOS = [3, 6, 9, 12, 15, 30, 45, 60];
```

Exemplo:

```javascript
const OPCOES_TEMPO_MINUTOS = [1, 5, 10, 20, 25, 45, 60, 90];
```

---

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript Vanilla
- Web Audio API
- Web Notifications API
- Local Storage

---

## Como Utilizar

```text
1. Abra o arquivo HTML no navegador.
2. Informe um nome para a atividade (opcional).
3. Clique em uma duração.
4. O temporizador inicia automaticamente.
5. Ajuste o tempo se necessário.
6. Aguarde o alerta ao final da contagem.
```

---

## Diferenciais

- Arquivo único HTML.
- Sem dependências externas.
- Funciona offline.
- Histórico automático.
- Tempos recentes inteligentes.
- Compatível com dispositivos móveis.
- Fácil de personalizar.

---

## Licença

Sinta-se à vontade para utilizar, adaptar e evoluir o projeto.
