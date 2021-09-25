---
title: 'HTMLMediaElement: canplaythrough'
slug: Web/API/HTMLMediaElement/canplaythrough_event
translation_of: Web/API/HTMLMediaElement/canplaythrough_event
---
L'événement **`canplaythrough`** est déclenché lorsque le user agent peut jouer le média et estime que suffisament de données ont été chargées pour le lire jusqu'au bout. (Sans s'arrêter afin de charger plus contenu en mémoire)

## Informations générales

- Spécification
  - : [HTML5 media](http://www.whatwg.org/specs/web-apps/current-work/multipage/the-video-element.html#event-media-canplaythrough)
- Interface
  - : Event
- Propagation
  - : Non
- Annulable
  - : Non
- Cible
  - : Element
- Action par défaut
  - : Aucune

## Propriétés

| Property                              | Type                                 | Description                                            |
| ------------------------------------- | ------------------------------------ | ------------------------------------------------------ |
| `target` {{readonlyInline}}     | {{domxref("EventTarget")}} | The event target (the topmost target in the DOM tree). |
| `type` {{readonlyInline}}       | {{domxref("DOMString")}}     | The type of event.                                     |
| `bubbles` {{readonlyInline}}    | {{jsxref("Boolean")}}         | Whether the event normally bubbles or not.             |
| `cancelable` {{readonlyInline}} | {{jsxref("Boolean")}}         | Whether the event is cancellable or not.               |

## Evénements liés

- {{event("playing")}}
- {{event("waiting")}}
- {{event("seeking")}}
- {{event("seeked")}}
- {{event("ended")}}
- {{event("loadedmetadata")}}
- {{event("loadeddata")}}
- {{event("canplay")}}
- {{event("canplaythrough")}}
- {{event("durationchange")}}
- {{event("timeupdate")}}
- {{event("play")}}
- {{event("pause")}}
- {{event("ratechange")}}
- {{event("volumechange")}}
- {{event("suspend")}}
- {{event("emptied")}}
- {{event("stalled")}}