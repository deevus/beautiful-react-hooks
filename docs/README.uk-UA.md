[![Build Status](https://travis-ci.org/beautifulinteractions/beautiful-react-hooks.svg?branch=master)](https://travis-ci.org/beautifulinteractions/beautiful-react-hooks)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![npm](https://img.shields.io/npm/v/beautiful-react-hooks)
![GitHub stars](https://img.shields.io/github/stars/beautifulinteractions/beautiful-react-hooks?style=social)


<div align="center">
  <p align="center">
    <img src="../logo.png" alt="Beautiful React Hooks" width="750px" />
  </p>
</div>
<br />
<div>
  <p align="center">
    Колекція красивих (також надіємось що корисних) Реакт хуків, для прискорення розробки ваших компонентів та хуків.
  </p>
</div>

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Спробуйте їх у дії тут 🌟
    </a>
  </p>
</div>

![Usage example](../usage_example.png)

<a href="https://github.com/beautifulinteractions/beautiful-react-hooks/">🇬🇧 English</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.zh-CN.md">🇨🇳 简体中文</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.it-IT.md">🇮🇹 Italiano</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.es-ES.md"> 🇪🇸 Español </a> | 🇺🇦 Ukrainian | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.pt-BR.md">🇧🇷 Brazilian Portuguese</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.pl-PL.md">🇵🇱 Polski </a>

## 💡 Чому? 

Кастомні Реакт хуки дозволяють абстрагувати бізнес логіку компонентів в окремі функції багаторазового використання.<br />
Досі, ми зауважили, що більшість хуків які ми створили і після цього поширили між нашими внутрішніми проектами, досить часто
мають аналогічну суть, що включають в себе виклик колбек функцій, подій та життєвих циклів компонентів.<br />
З цієї причини, ми спробували реалізувати цю суть в `beautiful-react-hooks`: колекцію (*сподіваємось*) корисних Реакт хуків,
для того щоб допомогти іншим компаніям та професіоналам пришвидшити їхній процес розробки.<br /><br />
Крім того, ми створили лаконічний, але конкретний API, з точки зору читабельності коду, маючи на меті
тримати криву вивчення настільки низькою, наскільки це можливо, тому це може бути використано та поширено у великих командах.



**-- Будь-ласка, перед використанням будь-яких хуків, прочитайте їхню документацію! --**

## ☕️ Особливості

* Лаконічний API
* Малий розмір та легкість
* Простий у вивченні
* Функціональний підхід
* Повністю написаний на JS(також TS типи підтримуються)

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Спробуйте їх у дії тут 🌟
    </a>
  </p>
</div>

## 🕺 Встановлення

Використовуючи `npm`:
```bash
$ npm install beautiful-react-hooks
```

Використовуючи `yarn`:

```bash
$ yarn add beautiful-react-hooks
```

## 🎨 Хуки

* [useGlobalEvent](useGlobalEvent.md)
* [usePreviousValue](usePreviousValue.md)
* [useValueHistory](useValueHistory.md)
* [useValidatedState](useValidatedState.md)
* [useMediaQuery](useMediaQuery.md)
* [useOnlineState](useOnlineState.md)
* [useViewportSpy](useViewportSpy.md)
* [useGeolocation](useGeolocation.md), [useGeolocationState](useGeolocationState.md) та [useGeolocationEvents](useGeolocationEvents.md)
* [useDrag](useDrag.md), [useDropZone](useDropZone.md) та [useDragEvents](useDragEvents.md)
* [useMouse](useMouse.md), [useMouseState](useMouseState.md) та [useMouseEvents](useMouseEvents.md)
* [useLifecycle](useLifecycle.md), [useDidMount](useDidMount.md) та [useWillUnmount](useWillUnmount.md)
* [useWindowResize](useWindowResize.md)
* [useWindowScroll](useWindowScroll.md)
* [useRequestAnimationFrame](useRequestAnimationFrame.md)
* [useTimeout](useTimeout.md)
* [useConditionalTimeout](useConditionalTimeout.md)
* [useInterval](useInterval.md)
* [useDebouncedFn](useDebouncedFn.md)
* [useThrottledFn](useThrottledFn.md)
* [useLocalStorage](useLocalStorage.md)

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Спробуйте їх у дії тут 🌟
    </a>
  </p>
</div>

## Внески

Ваші внески в проект дуже вітаються та потрібні.

Але для подання ваших кастомних хуків, переконайтесь що ви ознайомились з нашим гайдом для [ВНЕСКІВ](https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/CONTRIBUTING.md).

**Перед поданням** нового merge реквесту, будь-ласка переконайтеся:

1. Ви оновили версію package.json і повідомили про свої зміни в [CHANGELOG](https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/CHANGELOG.md) файлі
2. Переконайтеся, що ви запустили `npm test` і `npm build` перед поданням вашого merge реквесту.
3. Переконайтеся що ви додали документацію ваших кастомних хуків(*ви також можете використовувати [HOOK_DOCUMENTATION_TEMPLATE](https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/HOOK_DOCUMENTATION_TEMPLATE.md) для документації кастомних хуків*).
4. Переконайтеся що ви оновили `index.d.ts` файл з вашими типами хуків.

### За сприяння

* [React](https://reactjs.org/)
* [Mocha](https://mochajs.org/)
* [Chai](https://www.chaijs.com/)
* [@testing-library/react](https://testing-library.com/docs/react-testing-library/intro)
* [@testing-library/react-hooks](https://react-hooks-testing-library.com/) 


### Спонсорство

Ця бібліотека надана та спонсорується: 

<div>
  <p>
    <a href="https://beautifulinteractions.com/">
      <img src="https://beautifulinteractions.com/img/logo-colorful.svg" alt="Beautiful interactions" width="140px" />
    </a>
  </p>
</div>

У рамках нашого зобов'язання по підтримці та сприяння опенсорс спільноти.

---

Зображення надано [Freepik](https://www.flaticon.com/authors/freepik) з [www.flaticon.com](https://www.flaticon.com/free-icon/hook_1081812)
