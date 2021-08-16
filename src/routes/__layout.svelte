<div class="mdc-typography">
    <header class="mdc-top-app-bar">
        <div class="mdc-top-app-bar__row">
            <section class="mdc-top-app-bar__section mdc-top-app-bar__section--align-start">
                <button class="material-icons mdc-top-app-bar__navigation-icon mdc-icon-button" aria-label="Open navigation menu">menu</button>
                <span class="mdc-top-app-bar__title">Elevation</span>
            </section>
            <section class="mdc-top-app-bar__section mdc-top-app-bar__section--align-end" role="toolbar">
                <a href="/settings" class="material-icons mdc-top-app-bar__action-item mdc-icon-button" aria-label="Options">settings</a>
            </section>
        </div>
    </header>
    <main class="mdc-top-app-bar--fixed-adjust">
        <slot></slot>
    </main>
</div>
