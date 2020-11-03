<template>
    <div class="search-box-container">
        <h1>Homestays in Bangalore</h1>
        <p>Home is where the heart is. Discover your dream homestay today!</p>
        <div class="search-content-box">
            <div class="search-box box">
                <div class="bed-icon"></div>
                <input type="text" placeholder="Where are you going?" class="form-control"/>
            </div>
            <div class="check-in-out box">
                <div class="date-icon"></div>
                <div class="in-out-text">Check-in - Check-out</div>
            </div>
            <div class="adults-children-rooms box">
                <div class="user-icon"></div>
                <div class="adults-children-text">2 adults . 0 children . 1room</div>
            </div>
            <div class="search-box">
                <button class="btn btn-primary">Search</button>
            </div>
        </div>
    </div>
</template>
<style>
.search-content-box {
    background-color: #febb02;
    display: flex;
    align-items: center;
}
.box {
    background-color: #fff;
    height: 40px;
    display: flex;
    align-items: center;
    margin: 4px;
    padding: 10px;
}
.box:hover{
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
}
.search-box .form-control {
    border: 0;
    box-shadow: 0;
}
.search-box .form-control:focus {
    box-shadow: 0;
    border: 0;
    -webkit-box-shadow: 0;
}
</style>