CodeLab

Introduction to programming in Kotlin:

.Seu primeiro programa em kotlin ------------------------------------------------------------------------------------------------

. partes de uma função

<img width="462" height="376" alt="image" src="https://github.com/user-attachments/assets/edce888a-f280-43bc-ab32-41e27706b3f0" />

fun main () {
    println("Hello, android!")
}


.modificar o programa

<img width="446" height="394" alt="image" src="https://github.com/user-attachments/assets/bd93eccd-12e4-430e-a4d6-77e665624521" />

fun main () {
    println("Hello, android!")
    println("Hello, android!")
}

<img width="509" height="399" alt="image" src="https://github.com/user-attachments/assets/368a90b1-18ac-4aa0-80c9-c56c9cbe9551" />

fun main () {
    println("Hello, android!")
}

.Corrigir erros do codigo-----------------------

<img width="438" height="413" alt="image" src="https://github.com/user-attachments/assets/802e50f3-b41c-4e4d-a135-d413d4e96235" />

fun main() {
    println("Today is sunny!")
}

.Exercicios--------------------------------------

<img width="296" height="404" alt="image" src="https://github.com/user-attachments/assets/ae4c3df0-2468-4c3d-a707-5263764cd25a" />

fun main() {
    println("I'm")
    println("learning")
    println("Kotlin!")
}

<img width="406" height="479" alt="image" src="https://github.com/user-attachments/assets/c3deaafe-6615-42b1-bf9d-74dce1e5da58" />

fun main() {
    println("Tuesday")
    println("Thursday")
    println("Wednesday")
    println("Friday")
     println("Monday")
    
}

<img width="455" height="387" alt="image" src="https://github.com/user-attachments/assets/40cf82da-fd5c-4156-9d2d-e9c4db7100f0" />

fun main() {
    println("Tomorrow is rainy")
}

<img width="512" height="450" alt="image" src="https://github.com/user-attachments/assets/578f6ec9-44b0-4626-af98-28cc0763d473" />

fun main() {
    println("There is a chance of snow")
}

<img width="487" height="423" alt="image" src="https://github.com/user-attachments/assets/d6595ba5-c9ad-4b85-b78f-272d3a93bf8d" />

fun main() {
    println("Cloudy")
    println("Partly Cloudy") 
    println("Windy")
}
<img width="527" height="381" alt="image" src="https://github.com/user-attachments/assets/f404d604-c1e8-4fde-b5a7-8884c81dac12" />

fun main () {
    println("How's the weather today?")
}

.Criar variaveis em kotlin ------------------------

variaveis e tipos de dados:

<img width="848" height="301" alt="image" src="https://github.com/user-attachments/assets/84239fdd-2bd0-413a-8e04-c77db85149d0" />

Nome do canal = string
inscrições = int
likes = int
deslikes = int
foto do canal = bollean

Definir e usar variaveis

<img width="346" height="461" alt="image" src="https://github.com/user-attachments/assets/c9e2a1b8-3361-4c8e-b958-432052493b87" />

fun main() {
    val count: Int = 2
    println(count)
}

<img width="556" height="424" alt="image" src="https://github.com/user-attachments/assets/abbbe7a3-b854-4651-bb95-2e7c1b226d60" />

fun main() {
    val count: Int = 2
    println("You have $count unread messages.")
}

<img width="573" height="366" alt="image" src="https://github.com/user-attachments/assets/e242f263-4aac-4982-aa92-9f3ddbaa0471" />

fun main() {
    val count: Int = 20
    println("You have $count unread messages.")
}

<img width="1002" height="460" alt="image" src="https://github.com/user-attachments/assets/cdc00096-6552-4cea-8c0e-5894a7118b07" />

fun main() {
    val unreadCount = 10
    val readCount = 200
    println("You have ${unreadCount + readCount} total messages in your inbox.")
    
}

<img width="758" height="485" alt="image" src="https://github.com/user-attachments/assets/72163d34-5ea9-485d-86df-eacff9049142" />

fun main() {
    val numberOfPhotos = 400
    val photosDeleted = 30
    println("$numberOfPhotos photos")
    println("$photosDeleted photos deleted")
    println("${numberOfPhotos - photosDeleted} photos left")
}

Atualizar variaveis

<img width="572" height="417" alt="image" src="https://github.com/user-attachments/assets/06730ae9-53c5-4926-a5e5-34eb763da8cc" />

fun main() {
    var cartTotal = 3
    cartTotal = 20
    println("Total: $cartTotal")
}

<img width="498" height="392" alt="image" src="https://github.com/user-attachments/assets/c15a9c4e-577b-495e-a077-0c8b9cbb4d5f" />

fun main() {
    var cartTotal = 1000
    println("Total antes: $cartTotal")
    cartTotal = 20
    println("Total depois: $cartTotal")
}

<img width="633" height="405" alt="image" src="https://github.com/user-attachments/assets/b86009a1-8160-4aba-8b4a-5364fb820122" />

fun main() {
    var count = 10
    println("You have $count unread messages.")
    count = count + 90
    println("You have $count unread messages.")
}

<img width="615" height="439" alt="image" src="https://github.com/user-attachments/assets/61ad3199-522b-4aa6-9905-21514519c246" />

fun main() {
    var count = 90
    println("You have $count unread messages.")
    count++
    println("You have now $count unread messages.")
}

<img width="697" height="444" alt="image" src="https://github.com/user-attachments/assets/3a2a2a81-bb7c-42e4-b331-82b3d2a3a365" />

fun main() {
    var count = 109
    println("You have $count unread messages.")
    count--
    println("You have now $count unread messages.")
}

Outros tipos de dados

<img width="693" height="450" alt="image" src="https://github.com/user-attachments/assets/256a96b0-7ed6-4ae2-ae1b-3920ee15a855" />

fun main() {
    val trip1 = 32.20
    val trip2 = 400.10
    val trip3 = 10.72
    val totalTripLength = trip1 + trip2 + trip3
    println("$totalTripLength miles left to destination")
}

<img width="524" height="426" alt="image" src="https://github.com/user-attachments/assets/75ae384b-4d50-4d16-9963-0e6b28ad5f72" />

fun main() {
    val nextMeeting = "Next meeting: "
    val date = "august 5"
    val reminder = nextMeeting + date
    println(reminder)
}

<img width="652" height="383" alt="image" src="https://github.com/user-attachments/assets/3e9c01b8-9c1b-4abc-a4cf-4d0b1aa82d05" />

fun main() {
    val nextMeeting = "Next meeting: "
    val date = "august 5"
    val reminder = nextMeeting + date + " at work"
    println(reminder)
}

<img width="442" height="402" alt="image" src="https://github.com/user-attachments/assets/6934423a-9e14-4b9c-aa65-e8dd9e213e6a" />

fun main() {
    println("Say \"Bom dia\"")
}

<img width="561" height="434" alt="image" src="https://github.com/user-attachments/assets/ad93bd59-5792-4e2a-9c05-2f235604917a" />

fun main() {
    val notificacao: Boolean = true
    println(notificacao)
}

<img width="507" height="436" alt="image" src="https://github.com/user-attachments/assets/bd5c8985-6e76-4f2a-b071-3f7c8ab41b31" />

fun main() {
    val notificacao2: Boolean = false
    println(notificacao2)
}

<img width="715" height="452" alt="image" src="https://github.com/user-attachments/assets/03beca7c-35b0-47fe-95fb-8ef9c9722bfd" />

fun main() {
    val notificacao: Boolean = false
    println("As notificacoes tão  ativadas? " + notificacao)
}

Criar e usar funções

<img width="626" height="534" alt="image" src="https://github.com/user-attachments/assets/a307601e-b106-4bec-bc99-be00b96bcc4d" />

fun birthdayGreeting(): String {
    val nameGreeting = "Feliz aniversario, Rover!"
    val ageGreeting = "agora voce tem 5 anos!"
    return "$nameGreeting\n$ageGreeting"
}

fun main() {
    val greeting = birthdayGreeting()
    println(greeting)

    println() 
    println(birthdayGreeting())
}

adicionar parametros a funcao

<img width="780" height="509" alt="image" src="https://github.com/user-attachments/assets/6ce344a7-4201-4302-8583-fa88b0922c45" />

fun main() {
    println(aniversario("Rover"))
    println(aniversario("Rex"))
}
fun aniversario(nome: String): String {
    val mensagemParabens = "Feliz aniversário, $nome!"
    val mensagemIdade = "Você completou 5 anos!"
    return "$mensagemParabens\n$mensagemIdade"
}

<img width="667" height="494" alt="image" src="https://github.com/user-attachments/assets/991122f2-0394-4828-b1f6-0e511fbf8ef0" />

fun main() {
    println(aniversario("Rover", 5))
    println(aniversario(nome = "Rex", idade = 2))
}
fun aniversario(nome: String, idade: Int): String {
    val mensagemParabens = "Feliz aniversário, $nome!"
    val mensagemIdade = "Você completou $idade anos!"
    return "$mensagemParabens\n$mensagemIdade"
}

<img width="808" height="480" alt="image" src="https://github.com/user-attachments/assets/acc3e0ee-519c-45b0-b7db-857ddf3ba8d2" />

fun main() {
    println(aniversario(idade = 5))
    println(aniversario(nome = "Rex", idade = 2))
        println(aniversario(idade = 2))
}
fun aniversario(nome: String = "Rover", idade: Int): String {
    return "Feliz aniversário, $nome! Você completou $idade anos!"
}

Noções basicas de kotlin

<img width="733" height="486" alt="image" src="https://github.com/user-attachments/assets/1dafcd75-3a66-4f80-b90b-f2b270272e25" />

fun main() {
    val programa = "Curso de Kotlin"
    var mensagem = "olá"
    println(mensagem)

    mensagem = "oi"
    println(mensagem)

    mensagem = "tchau"
    println(mensagem)

    mensagem = "Bem vindo"
    println(mensagem)
}

<img width="602" height="381" alt="image" src="https://github.com/user-attachments/assets/19cdf0e2-52e9-45e7-b774-64b17eb556a6" />

fun main() { 
    println("New chat message from a friend")
}

<img width="942" height="437" alt="image" src="https://github.com/user-attachments/assets/446b7cf3-a59e-47d6-a891-796351d356a3" />

fun main() {
    var discountPercentage: Int = 0
    var offer: String = ""
    val item = "Google Chromecast"
    discountPercentage = 20
    offer = "Sale - Up to $discountPercentage% discount on $item! Hurry up!"
    println(offer)
}

<img width="669" height="426" alt="image" src="https://github.com/user-attachments/assets/7b0d4fef-5bfa-4f57-9cf9-aba1a384eab5" />

fun main() {
    val numberOfAdults = 20
    val numberOfKids = 30
    val total = numberOfAdults + numberOfKids
    println("The total party size is: $total")
}

<img width="1229" height="438" alt="image" src="https://github.com/user-attachments/assets/26bbea93-f447-4bcd-998d-9937366ec12c" />

fun main() {
    val baseSalary = 5000
    val bonusAmount = 1000
    val totalSalary = baseSalary + bonusAmount
    println("Congratulations for your bonus! You will receive a total of $totalSalary (additional bonus).")
}

<img width="903" height="467" alt="image" src="https://github.com/user-attachments/assets/aff4539e-1ecd-4a3d-8ee5-041f5347c1dc" />

fun main() {
    val firstNumber = 10
    val secondNumber = 5
    val thirdNumber = 8
    val result = add(firstNumber, secondNumber)
    val anotherResult = add(firstNumber, thirdNumber)
    val subResult = subtract(firstNumber, secondNumber)
    val subAnotherResult = subtract(firstNumber, thirdNumber)

    println("$firstNumber + $secondNumber = $result")
    println("$firstNumber + $thirdNumber = $anotherResult")
    println("$firstNumber - $secondNumber = $subResult")
    println("$firstNumber - $thirdNumber = $subAnotherResult")
}
fun add(a: Int, b: Int): Int {
    return a + b
}
fun subtract(a: Int, b: Int): Int {
    return a - b
}

<img width="1100" height="440" alt="image" src="https://github.com/user-attachments/assets/c2db5177-2de1-479e-9e92-aa59601e7b4a" />

fun main() {
    val operatingSystem = "Chrome OS"
    val emailId = "sample@gmail.com"

    println(displayAlertMessage(operatingSystem, emailId))
}
fun displayAlertMessage(operatingSystem: String, emailId: String): String {
    return "There's a new sign-in request on $operatingSystem for your Google Account $emailId."
}

<img width="1202" height="502" alt="image" src="https://github.com/user-attachments/assets/6cd4c788-0035-434b-9b07-4aaea7f58e06" />

fun main() {
    val firstUserEmailId = "user_one@gmail.com"
    println(displayAlertMessage(emailId = firstUserEmailId))
    println()
    val secondUserOperatingSystem = "Windows"
    val secondUserEmailId = "user_two@gmail.com"
    println(displayAlertMessage(emailId = secondUserEmailId, operatingSystem = secondUserOperatingSystem))
    println()
    val thirdUserOperatingSystem = "Mac OS"
    val thirdUserEmailId = "user_three@gmail.com"
    println(displayAlertMessage(emailId = thirdUserEmailId, operatingSystem = thirdUserOperatingSystem))
    println()
}
fun displayAlertMessage(emailId: String, operatingSystem: String = "Unknown OS"): String {
    return "There's a new sign-in request on $operatingSystem for your Google Account $emailId."
}

<img width="965" height="455" alt="image" src="https://github.com/user-attachments/assets/d7b98161-720c-4e62-8fd2-26bf06254d5e" />

fun main() {
    val passosDados = 4000
    val caloriasQueimadas = calcularCaloriasPorPassos(passosDados)
    println("Caminhar $passosDados passos queima $caloriasQueimadas calorias")
}

fun calcularCaloriasPorPassos(numeroDePassos: Int): Double {
    val caloriasPorPasso = 0.04
    val totalCalorias = numeroDePassos * caloriasPorPasso
    return totalCalorias
}

<img width="872" height="434" alt="image" src="https://github.com/user-attachments/assets/77406431-10b7-48cf-b5c4-74c5fec6e075" />

fun main() {
    val tempoHoje = 300
    val tempoOntem = 250
    val passouMaisTempo = compararTempoSmartphone(tempoHoje, tempoOntem)
    println(passouMaisTempo) 
}
fun compararTempoSmartphone(tempoHoje: Int, tempoOntem: Int): Boolean {
    return tempoHoje > tempoOntem
}

<img width="1117" height="552" alt="image" src="https://github.com/user-attachments/assets/3d008942-93e7-4e4f-aa95-392756a8f751" />

fun main() {
    mostrarClima("Ankara", 27, 31, 82)
    mostrarClima("Tokyo", 32, 36, 10)
    mostrarClima("Cape Town", 59, 64, 2)
    mostrarClima("Guatemala City", 50, 55, 7)
}
fun mostrarClima(cidade: String, temperaturaMin: Int, temperaturaMax: Int, chanceChuva: Int) {
    println("City: $cidade")
    println("Low temperature: $temperaturaMin, High temperature: $temperaturaMax")
    println("Chance of rain: $chanceChuva%")
    println()
}

<img width="1084" height="459" alt="image" src="https://github.com/user-attachments/assets/90fffdc2-2577-423d-8b6d-1f41215ca94d" />

fun main() {
    println("Use the val keyword when the value doesn't change.")
    println("Use the var keyword when the value can change.")
    println("When you define a function, you define the parameters that can be passed to it.")
    println("When you call a function, you pass arguments for the parameters.")
}

<img width="992" height="451" alt="image" src="https://github.com/user-attachments/assets/dcda211a-e07c-4786-a521-fe01b56a627f" />

fun main() {
    val discountPercentage = 20
    val item = "Google Chromecast"
    val offer = "Sale - Up to $discountPercentage% discount off $item! Hurry Up!"

    println(offer)
}

<img width="756" height="447" alt="image" src="https://github.com/user-attachments/assets/03e0a8df-87d3-471a-8e01-398808031a0c" />

fun main() {
    val numberOfAdults = 20
    val numberOfKids = 30
    val total = numberOfAdults + numberOfKids
    println("The total party size is: $total")
}

<img width="999" height="499" alt="image" src="https://github.com/user-attachments/assets/cc441672-f75c-435a-b826-4b698f6cefc9" />

fun main() {
    val firstNumber = 10
    val secondNumber = 5
    val thirdNumber = 8
    val result = add(firstNumber, secondNumber)
    println("$firstNumber + $secondNumber = $result")
    val anotherResult = subtract(firstNumber, thirdNumber)
    println("$firstNumber - $thirdNumber = $anotherResult")
}
fun add(firstNumber: Int, secondNumber: Int): Int {
    return firstNumber + secondNumber
}
fun subtract(firstNumber: Int, secondNumber: Int): Int {
    return firstNumber - secondNumber
}

<img width="1140" height="464" alt="image" src="https://github.com/user-attachments/assets/7e653c37-9d5b-4500-be84-681a60370cd9" />

fun main() {
    val message1 = displayAlertMessage(emailId = "user@example.com")
    println(message1)
    val message2 = displayAlertMessage("MacOS", "user@example.com")
    println(message2)
}
fun displayAlertMessage(
    operatingSystem: String = "Unknown OS",
    emailId: String
): String {
    return "There is a new sign-in request on $operatingSystem for your Google Account $emailId."
}

<img width="1021" height="449" alt="image" src="https://github.com/user-attachments/assets/5eeff4a7-8dea-42b5-afef-d0d00eacce36" />

fun main() {
    val passos = 7000
    val caloriasQueimadas = passosParaCalorias(passos)
    println("Caminhando $passos passos você queima $caloriasQueimadas calorias")
}
fun passosParaCalorias(numeroDePassos: Int): Double {
    val caloriasPorPasso = 0.02
    val totalDeCalorias = numeroDePassos * caloriasPorPasso
    return totalDeCalorias
}

<img width="987" height="477" alt="image" src="https://github.com/user-attachments/assets/c3c6ca09-cb1b-450c-b2cb-181edc77a1a9" />

fun compararTempo(tempoHoje: Int, tempoOntem: Int): Boolean {
    return tempoHoje > tempoOntem
}
fun main() {
    println("Passei mais tempo no celular hoje: ${compararTempo(300, 250)}")
    println("Passei mais tempo no celular hoje: ${compararTempo(300, 300)}")
    println("Passei mais tempo no celular hoje: ${compararTempo(200, 220)}")
}

<img width="1002" height="570" alt="image" src="https://github.com/user-attachments/assets/32670098-6f61-43d5-a726-967523ff0e9a" />

fun mostrarClimaCidade(nomeCidade: String, tempMin: Int, tempMax: Int, chanceChuva: Int) {
    println("Cidade: $nomeCidade")
    println("Temperatura mínima: $tempMin, Temperatura máxima: $tempMax")
    println("Chance de chuva: $chanceChuva%")
    println()
}

fun main() {
    mostrarClimaCidade("Ancara", 27, 31, 82)
    mostrarClimaCidade("Tóquio", 32, 36, 10)
    mostrarClimaCidade("Cidade do Cabo", 59, 64, 2)
    mostrarClimaCidade("Cidade da Guatemala", 50, 55, 7)
}



