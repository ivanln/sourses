Как сохранять переменные при закрытии приложения

Свойства - параметры - добавить переменную

добавить в код using <Название приложения>.Properties;

Как использовать:
textBox1.Text = Settings.Default["Название переменной"].ToString();
Settings.Default["Название переменной"] = textBox1.Text;
Settings.Default.Save();
