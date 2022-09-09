«B2» Теги використані відповідно до їх семантичного змісту.

«B10» Всі нові іконки з форм додані в SVG-спрайт icons.svg.

Оформлення
«C1» Виконано оформлення елементів форми підписки на розсилання у футері.

«C2» Виконано оформлення елементів форми заявки у модальному вікні.

«C3» При отриманні інпутом фокусу, його рамка та іконка змінюють колір (як показано на макеті).

«C4» Оригінальний чекбокс про прийняття ліцензійної угоди у формі заявки прихований.

«C5» Оформлення «чекбокса» про прийняття ліцензійної угоди зроблено вручну, за допомогою векторного зображення галочки з SVG-спрайту.

«C6» Для всіх ефектів ховера і фокуса (колір, фон, тінь) зроблені переходи. час - 250ms, функція розподілу часу - cubic-bezier(0.4, 0, 0.2, 1).

/_ --help-- _/
/_ p,
h1,
h2,
h3,
.page-nav-list,
.logo,
.contacts,
.footer-address {
outline: 2px solid tomato;
}
li {
outline: 2px solid blueviolet;
}
.coteiner {
outline: 2px solid teal;
}
.section {
outline: 2px solid green;
} _/

/_ .portfolio-filter li + li {
margin-left: 8px;
} _/
/_ .portfolio-filter + .portfolio-galery {
margin-top: 50;
} _/

/_ .benefits-list .icon {
width: 70px;
height: 70px;
} _/

/_ .btn-secondary {
background-color: var(--color-bg-secondary);
color: var(--color-nav-and-title);
}
.btn-primary {
background-color: var(--color-accent);
color: var(--color-text-theme-dark);
} _/

/_ .portfolio-galery-link:hover,
.portfolio-galery-link:focus{
outline: 5px solid teal;
box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.12), 0px 4px 4px rgba(0, 0, 0, 0.06),
1px 4px 6px rgba(0, 0, 0, 0.16);
} _/

.backdrop {

/_ щоб нічого не перекривало -z-index_/

}

/_ коли сховане _/
.backdrop.is-hidden .modal {
/_ transform-origin: top right; _/
border-radius: 50%;
background-color: var(--color-accent);
transform: background-color var(--modal-animetion-time-func);
transform: translate(100%, 100%) scale(2) rotate(720deg);
/_ transition: transform var(--modal-animetion-time-func),
background-color var(--modal-animetion-time-func) 1000ms,
border-radius var(--modal-animetion-time-func); _/
}

/_ коли вже відкрите _/
.modal {

min-width: 528px;
min-height: 581px;

;
transform: background-color var(--modal-animetion-time-func);
box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14),
0px 2px 1px rgba(0, 0, 0, 0.2);
border-radius: 4px;
transform: translate(-50%, -50%) scale(1) rotate(0deg);

transition: transform var(--modal-animetion-time-func),
background-color var(--modal-animetion-time-func) 1000ms,
border-radius var(--modal-animetion-time-func); \_/
}

/\_ .close.is-hidden .modal {
transform: translate(-50%, -50%) scale(0) rotate(0deg);
background-color: tomato;
} \*/
