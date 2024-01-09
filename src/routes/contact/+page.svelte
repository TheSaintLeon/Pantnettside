<div class="header">
    <div class="inner">
        <h1>Pante kampanjen - Contact</h1>
        <div class="contact">
            <span>email@email.com</span>
            <span>
                <span>
                    Hvorfor bør man pante? Det er jo bra fordi vi forsøppler
                    ikke naturen og vi sparer penger!
                </span>
            </span>
        </div>
    </div>
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
        position: relative;
        animation: fadeout 500ms ease;
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
        margin-top: 100px;
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

    .contact {
        display: flex;
        flex-direction: column;
        align-items: center;
        background: rgba(0, 0, 0, 0.5);
        padding: 15px;
        border-radius: 10px;
        width: 500px;
        font-size: 24px;
        margin-top: 10px;
    }
</style>
