# odin-dashboard

<div class="wrapper-header">
                <i class="fa fa-search" aria-hidden="true"></i>
                <input type="text" id="input-header">
                <i class="fa fa-bell" aria-hidden="true"></i>
                <img src="#" alt="a photo">
                <h1>Morgan Stanley</h1>
            </div>



            * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(4, 1fr);
    gap: 20px;
    border: 1px solid black;
    height: 100vh;

}

.container:nth-of-type(1) {
    border: 2px solid red;
    background-color: red;
    grid-row: span 4;
}

.container:nth-of-type(2) {
    border: 2px solid black;
    background: black;
    grid-column-start: 2;
    grid-column-end: 5;
}

.container:nth-of-type(3) {
    border: 2px solid grey;
    grid-column: 2/5;
    grid-row: 2/5;
}


.header .wrapper-header {
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;

}

.wrapper-header .first-row:nth-of-type(1) {
    grid-column: 1/2;
}

.wrapper-header .first-row:nth-of-type() {
    grid-column: 2/3;
}



 <div class="second-row">
                    <img src="#" alt="photo">
                    <h3>Hi there</h3>
                    <h1>Morgan Stanley</h1>
                    <ul>
                        <li><a href="#">New</a></li>
                        <li><a href="#">upload</a></li>
                        <li><a href="#">share</a></li>
                    </ul>

                </div>