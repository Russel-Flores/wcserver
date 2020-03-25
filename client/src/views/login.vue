<template>
    <form>
        <div class="container">
            <div class="row h-100 justify-content-center align-items-center">
                <div class="col-md-5">
                    <h2>Login</h2>
                    <div class="form-group text-left">
                        <label for="email">Email Address</label>
                        <input type="text" class="form-control text-center" name="email" id="email" placeholder="Email Address" v-model="email"/>
                    </div>
                    <div class="form-group text-left ">
                        <label for="password">Password</label>
                        <input type="password" class="form-control text-center" name="password" id="password" placeholder="Password" v-model="password"/>
                    </div>
                    <div class="form-group">
                        <button class="btn btn-lg btn-success m-5" type="submit"> Login </button>
                        <button class="btn btn-lg btn-danger m-5" type="submit"> Cancel </button>
                    </div>
                </div>
            </div>
        </div>
    </form>
</template>

<style>
form{
    background-image: linear-gradient(rgba(0,0,0,0.1),rgba(0,0,0,0.3)),url('../../../images/img2.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

.col-md-5, .h2{
    margin: 60px;
}

.col-md-5{
    color: black;
}

button {
  color: white;
  border: none;
  cursor: pointer;
  opacity: 0.9;
}

button:hover {
  opacity:1;
}

</style>
