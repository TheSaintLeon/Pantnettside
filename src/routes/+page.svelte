<div class="header">
    <div class="inner">
        <h1>Pante Kampanjen</h1>
        <a class="btn" target="_blank" href="https://bludood.com">
            Our Partner</a
        >
    </div>

    <a class="btn contact" href="contact">Contact Support</a>
</div>

<style>
    .header {
        background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
            url(https://www.arstadposten.no/wp-content/uploads/2021/02/Rema-1000-pant-777x437.jpg);
        background-position: center;
        background-size: cover;
        height: 100vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        position: relative;
        animation: fadein 500ms ease;
    }

    @keyframes fadein {
        from {
            opacity: 0;
        }

        to {
            opacity: 1;
        }
    }

    .inner {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        animation: appear 1000ms ease;
    }

    @keyframes appear {
        from {
            transform: translateY(-20%);
            opacity: 0;
        }

        to {
            transform: translateY(0%);
            opacity: 1;
        }
    }

    .header h1 {
        font-size: 64px;
    }

    .header p {
        font-size: 30px;
    }

    .header .btn {
        all: unset;
        display: flex;
        line-height: 1;
        background: rgba(0, 0, 0, 0.5);
        padding: 15px;
        border-radius: 9999px;
        cursor: pointer;
    }

    .header .contact {
        position: absolute;
        bottom: 15px;
    }
</style>
