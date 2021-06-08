<template>
  <div class="mx-20 m-8">
    <div>
      <h1 class="text-center text-lg font-bold text-black">
        Seja uma Compiladora!
      </h1>
      <p class="text-center font-medium text-gray-600">
        Faça sua incrição abaixo
      </p>
    </div>

    <div class="p-2">
      <div
        class="
          bg-white
          rounded 
          
        "
      >
        <form action="" method="get" name="myForm" class="flex justify-center rounded-lg">
          <div class="flex border-black border border-t border-b border-r rounded-lg">
            <div class="p-4">
                <div class="flex flex-col">
                  <label for="fname">Name</label>
                  <input type="text" id="fname" name="fname" />
                  <hr class="border-black border-b" />
                  <br /><br />
                </div>

                <div class="flex flex-col">
                  <label for="lname">E-mail</label>
                  <input type="text" id="lname" name="mail" />
                  <hr class="border-black border-b" />
                  <br /><br />
                  <input type="text" name="mail" /><br />
                </div>
            </div>

            <div class="bg-black text-white w-44 h-44  flex justify-center">
              <button class="w-64 border-black border border-t border-b border-r rounded-lg">
                Enviar
              </button>
            </div>

          </div>
        </form>
      </div>
    </div>
  </div>
</template>