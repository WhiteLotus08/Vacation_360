Abrir una sesion de Terminal y ejecutar el comando:

sudo gem install cocoapods

Te pedira password e instalara todas las gemas necesarias y los archivos que necesita el cocoapods

despues le das el path donde tienes el proyecto en este caso vacations 360

cd ~/path/vacation360

se crea el pod con el comando

pod init  /en nuestro caso ya esta credo

despues se habre el archivo podfile que se creo en el folder vacation360 y se agrega el siguiente codigo borrando el 
demas que hay

target"Vacation 360" do
pod 'GVRSDK'
end

Esto le dira al Cocoapods que se incluira el GVRSDK como dependencia del proyecto.

despues en la terminal das el comando
pod install

Asi se va a instalar el Google VR SDK ahora se ceara un archivo llamado vacation 360.xcworkspace es el que se utilizara 
de ahora en adelante, en nuestro caso ya esta creado.


 