<template>
    <div class="container">
        <div class="text-5xl py-2">Components page</div>
        
        <div class="mt-10">
            <p class="text-3xl font-bold mb-1">Buttons</p>

            <div>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
                    Button
                </button>
            </div>
        </div>

        <div class="mt-10">
            <p class="text-3xl font-bold mb-1">Cards</p>
            <div class="bg-slate-200 rounded-xl p-4 max-w-[300px]">
                Card component dummy
            </div>
        </div>
    </div>

    <div class="card-details">
        <div class="card-title">
            <h3>Rsv recovery</h3>
            <div class="card-price">$85</div>
        </div>
        <div class="card-info">
            <i class="fa fa-laptop" style="font-size:12px"></i> <!-- Replace with your desired icon class -->
            <span>Remote</span>
        </div>
        <div class="card-info">
            <i class="fa fa-calendar" style="font-size:12px"></i>
            <span>Before Fri, 19 Apr</span>
        </div>
        <div class="card-action">
            <span>Open</span>
            <i class="fa fa-user" style="font-size:24px; margin-left: auto;"></i> <!-- Replace with your desired icon class -->
        </div>
    </div>
  
</template>

<script>
export default {

}
</script>

<style>
.card-details {
    border: 1px solid #e2dfe4;
    background-color: rgb(245, 242, 248);
    border-radius: 5px;
    padding: 1px 5px 20px 10px;
    margin: 10px;
    width: 290px;
    box-shadow: 0 2px 4px #d8c5e2e5;
}

.card-title {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.card-price {
    font-weight: bold;
    font-size: 16px;
    margin-left: auto;
}

.card-info {
    display: flex;
    align-items: center;
    margin-bottom: 5px;
    margin-right: 5px;
}

.card-info i {
    margin-right: 5px;
}

.card-action {
    display: flex;
    justify-content: left;
    margin-top: 10px;

}

.card-action i {
    margin-left: auto;
    margin-right: 5px;
}

.card-action span {
    font-size: 16px;
    font-weight: bold; /* This will make the text bold */
    padding: auto;
}
</style>
