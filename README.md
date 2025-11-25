# New-project-body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: #ddd;
    margin: 0;
}

.grid {
    display: grid;
    grid-template-columns: repeat(3, 120px);
    grid-template-rows: repeat(3, 120px);
    gap: 10px;
    background: white;
    padding: 10px;
    border: 2px solid #0077ff;
}

.box {
    border-radius: 4px;
}

/* Colors */
.red {
    background: red;
}

.blue {
    background: rgb(0, 102, 255);
}

.black {
    background: black;
}