error id: file://<HOME>/Documents/SEM%20-%20VI%20/DSBDAL/31480_DSBDAL_13.scala:[776..777) in Input.VirtualFile("file://<HOME>/Documents/SEM%20-%20VI%20/DSBDAL/31480_DSBDAL_13.scala", "object QuickSortApp {
  def quickSort(arr: List[Int]): List[Int] = {
    if (arr.length <= 1) arr
    else {
      val pivot = arr(arr.length / 2)
      quickSort(arr.filter(_ < pivot)) :::
      arr.filter(_ == pivot) :::
      quickSort(arr.filter(_ > pivot))
    }
  }

  def main(args: Array[String]): Unit = {
    val nums = List(9, 4, 6, 2, 8, 1)
    println(s"Original List: $nums")
    val sortedNums = quickSort(nums)
    println(s"Sorted List (Quick Sort): $sortedNums")
  }
}


object QuickSortApp2 {
  def quickSort(arr: List[Int]): List[Int] = {
    if (arr.length <= 1) arr
    else {
      val pivot = arr(arr.length / 2)
      quickSort(arr.filter(_ < pivot)) :::
      arr.filter(_ == pivot) :::
      quickSort(arr.filter(_ > pivot))
    }
    }

    def 
  }
")
file://<HOME>/Documents/SEM%20-%20VI%20/DSBDAL/file:<HOME>/Documents/SEM%2520-%2520VI%2520/DSBDAL/31480_DSBDAL_13.scala
file://<HOME>/Documents/SEM%20-%20VI%20/DSBDAL/31480_DSBDAL_13.scala:33: error: expected identifier; obtained rbrace
  }
  ^
#### Short summary: 

expected identifier; obtained rbrace