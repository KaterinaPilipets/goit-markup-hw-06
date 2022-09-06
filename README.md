«D8» Поява і приховування модального вікна анімовано за допомогою переходу з довільним ефектом, наприклад scale або translate, і opacity.

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
