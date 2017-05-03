# answerCell
public boolean answerCell(boolean isMorning, boolean isMom, boolean isAsleep) {
  if (isMom && isMorning && !isAsleep){
    return true;
  }
  else if(!isAsleep && !isMorning){
    return true;
  }
  else if(isAsleep){
    return false;
  }
  else return false;
}
