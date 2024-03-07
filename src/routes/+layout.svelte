<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo" title="Вернуться на главную страницу">Всеволод Русакевич</a>
        <div class="nav-links">
            <a href="/about" class="link">Обо мне</a>
            <a href="/block" class="link">Блог</a>
            <a href="/prodjects" class="link">Портфолио</a>
            <a href="/contact" class="link">Контакты</a>
        </div>
    </div>
</nav>

<div class="container">
    <!--Страницы будут добавлены ниже-->
    <slot></slot>
</div>

<style>
    .container {
        max-width: 1400px;
        margin: 50px auto;
    }
</style>