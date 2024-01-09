<div class="navbar">
    <div class="links">
        <a href="/">Home</a>
        <a href="/">Help</a>
    </div>
    <div class="actions"></div>
</div>

<style>
    .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px;
        position: fixed;
        width: 100vw;
        z-index: 999;
    }

    .logo {
        width: 200px;
    }

    .links {
        display: flex;
        gap: 10px;
    }

    .links a {
        font-size: 20px;
        color: white;
    }

    .actions {
        width: 200px;
        display: flex;
        justify-content: flex-end;
        gap: 10px;
        margin-right: 10px;
    }

    .actions a {
        color: white;
    }
</style>
