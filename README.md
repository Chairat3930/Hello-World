# Calculator

by Chairat Wonrattanachai,
673450393-0,
Computer and Infomation Science, KKU

# การรับและการแสดงผลข้อมูล

รับข้อมูลจากผู้ใช้งาน และทำงานผ่านการกดปุ่มเพื่อคำนวนตัวเลข

## ปุ่มบวก

```
private void button1_Click(object sender, EventArgs e)
{
    // ข้อความตัวอักษร
    string inputNum1 = num1.Text;
    string inputNum2 = num2.Text;
    // convert string to number (integer)
    int iNum1 = Int32.Parse(inputNum1);
    int iNum2 = Int32.Parse(inputNum2);
    // int ทำให้เราสามารถทำการ + - * / ได้
    int iResult = iNum1 + iNum2;
    // ที่ตัวแปรชื่อ result
    // มีคุณสมบัติชื่อ Text
    result.Text = iResult.ToString();
}
```

### รับข้อมูล
            string inputNum1 = Num1.Text;
            string inputNum2 = Num2.Text;

### แปลงชนิดของข้อมูล
 int iNum1 = Int32.Parse(inputNum1);
 int iNum2 = Int32.Parse(inputNum2);
### คำนวนผลลัพท์
           int iResult = iNum1 + iNum2;

### แสดงผล

ตัวอย่าง
  Result.Text = iResult.ToString();

## ปุ่มลบ
        private void button4_Click(object sender, EventArgs e)
        {
            string inputNum1 = Num1.Text;
            string inputNum2 = Num2.Text;
            // convert string to number (integer)
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2);
            // int ทำให้เราสามารถทำการ + - * / ได้
            int iResult = iNum1 - iNum2;
            // ที่ตัวแปรชื่อ result
            // มีคุณสมบัติชื่อ Text
            Result.Text = iResult.ToString();

## ปุ่มคูณ

        private void button2_Click(object sender, EventArgs e)
        {
            string inputNum1 = Num1.Text;
            string inputNum2 = Num2.Text;
            // convert string to number (integer)
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2);
            // int ทำให้เราสามารถทำการ + - * / ได้
            int iResult = iNum1 * iNum2;
            // ที่ตัวแปรชื่อ result
            // มีคุณสมบัติชื่อ Text
            Result.Text = iResult.ToString();

## ปุ่มหาร
        private void button5_Click(object sender, EventArgs e)
        {
            string inputNum1 = Num1.Text;
            string inputNum2 = Num2.Text;
            // convert string to number (integer)
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2);
            // int ทำให้เราสามารถทำการ + - * / ได้
            int iResult = iNum1 / iNum2;
            // ที่ตัวแปรชื่อ result
            // มีคุณสมบัติชื่อ Text
            Result.Text = iResult.ToString();
        }

## ปุ่มลบข้อมูล
        private void button3_Click(object sender, EventArgs e)
        {
            textBox3.Clear();
