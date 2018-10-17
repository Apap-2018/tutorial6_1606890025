1. Mengapa perlu menginisiasi object PilotModel, sedangkan yang di test hanya FlightModel?

karena data pada FlightModel yang ditest, memiliki kolom pilot yang berisi id dari pilot coki

2. Jelaskan apa yang akan terjadi jika object PilotModel dihapus dan tidak dilakukan setPilot pada FlightModel?

maka test assertThat(found.get(), Matchers.equalTo(flightModel)) akan gagal

3. Jelaskan apa yang dilakukan oleh code


