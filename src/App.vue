<template>
    <div class="overlay">
        <div class="modal">
            <textarea name="note" id="" cols="30" rows="10"></textarea>
            <div class="buttons">
                <button class="save">Save</button>
                <button class="close">Close</button>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="header">
            <h2>Notes</h2>
            <button>+</button>
        </div>

        <div class="note-container">
            <div class="card">
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eveniet quod dolorum laboriosam perspiciatis
                    distinctio vitae!</p>
                <p class="date">19/10/23</p>
            </div>
        </div>
    </div>
</template>

<style>
.container {
    width: 60vw;
    margin: 0 auto;
}

.header {
    padding-top: 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.header h2 {
    font-size: 36px;
    font-weight: bold
}

.header button {
    border-radius: 100%;
    height: 40px;
    width: 40px;
    border: none;
    font-size: 24px;
}

.card {
    width: 40%;
    margin-top: 20px;
    padding: 20px 14px;
    background-color: #23dcff;
    color: #000;
    border-radius: 10px;
    height: 250px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.card p {
    font-size: 16px;
}

.card .date {
    font-size: 12px;
    text-align: right;
    font-weight: bold;
}

.overlay {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.7);
    display: flex;
    justify-content: center;
    align-items: center;
}

.modal {
    background-color: #fff;
    padding: 20px;
    width: 40vw;
}

textarea {
    width: 100%;
    height: 200px;
    outline: none;
    border: 2px solid #456db4;
    font-size: 16px;
    resize: none;
}
.buttons {
    display: flex;
    justify-content: end;
}
.buttons .save {
    background-color: #456db4;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    margin-right: 10px;
}
.buttons .close {
    background-color: #fff;
    color: #456db4;
    border: 2px solid #456db4;
    padding: 10px 20px;
    border-radius: 5px;
}
</style>